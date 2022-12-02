# Security information about OmegaT

OmegaT is the translation tool selected for the language tasks of various projects. cApStAn is responsible for customizing this tool so that it can interact optimally with the XLIFF files that will be prepared for those projects, and to streamline language tasks and reduce support requests. 

OmegaT will be installed from a designated installer that will be downloaded from the [http://omegat.org](http://omegat.org) website. The customization consists of editing or adding some settings files to the default installation and an executable developed by cApStAn will be provided to users to save them the effort of doing the customization manually. If you prefer to customize manually, that's also possible, just let us know.

The purpose of the present document is to provide information relevant for IT departments who must ensure that any software installed in their organization does not pose any security threads. 

## Updating Windows malware definitions

Before downloading the installation files (OmegaT installer and customization utility), you should update Windows Defender's definitions. On the command prompt as administrator: 

  1. Change directory to `C:\Program Files\Windows Defender`
  1. Run `MpCmdRun.exe -removedefinitions -dynamicsignatures`
  1. Run `MpCmdRun.exe -SignatureUpdate`

Source: [https://www.microsoft.com/en-us/wdsi/definitions](https://www.microsoft.com/en-us/wdsi/definitions)

## Integrity verification <= UPDATE NEEDED

You can check the integrity of the file to make sure that, after download, you have the same file that is available for download in the repository of OmegaT binaries. 

On Windows, you can compute the cryptographic hash values of a binary file with the **File Checksum Integrity Verifier** utility (check [this](https://support.microsoft.com/en-us/help/889768/how-to-compute-the-md5-or-sha-1-cryptographic-hash-values-for-a-file) for further information and download the utility).

The correct hashes of the 64-bit installer (OmegaT_4.1.5_04_Beta_Windows_64.exe) are: 

- SHA1:	`9a7560368ca11255c4359c2ed225eb0bd7a7fbe0`
- MD5:	`8c4dd481b715396979ba6ec5e2d1e9a8`

The correct hashes of the 32-bit installer (OmegaT_4.1.5_04_Beta_Windows.exe) are: 

- SHA1:	`682e38f718ef8736ccb978f45dd13da75184648a`
- MD5:	`608417d270bc67f153d92e243abd1f96`

These values are taken from the [official OmegaT download page](https://sourceforge.net/projects/omegat/files/OmegaT%20-%20Latest/OmegaT%204.1.5%20update%204/).

If you obtain the same values, you can be certain that you have the same file as it’s available for download and that it’s safe to whitelist it. 

## Java maintenance

OmegaT is developed in Java and needs JRE to run. The OmegaT installers we recommend include the version of JRE that OmegaT needs, and that JRE would be uninstalled when OmegaT is uninstalled. However, in any case, as Java can be a security risk if it’s not kept up to date, it’s worth maintaining that version of JRE up to date after installed if necessary.

## Data leakage

OmegaT can check for new versions, get MT results, get glossary matches from TaaS, download MediaWiki links and use them as source files, have remote files on HTTP, Git and SVN servers mapped locally, and then there's SVN/Git team project functionality. We're not using any of those functions in the translation of the PISA/PIAAC materials, which means we won't instruct users to configure or use them. 

However, it’s always possible that the user unilaterally uses them. If this is a concern for the organization, OmegaT could be made to work in a complete offline manner, namely it could be started with a non-functional proxy, so it won't connect to internet at all (specifying a non-existing proxy server, e.g. 270.270, in the startup parameters in the `OmegaT.l4J.ini` file). In other words, it’s up to the organization and their internal policy to decide how much access to the internet it must be allowed to OmegaT. 

## Open source

In case of any concerns about vulnerabilities in OmegaT against viruses or other malware, the source code is freely available and used to build software packages in several OS distributions. Any Java engineer can inspect the code and conduct any tests to assess its robustness and reliability.

## Endorsement by big organizations

The European Commission has been promoting the use of open-source software namely within its [R&D programmes]. It is in this context that open source applications like OmegaT are being used in DGT (the European Commission’s Directorate-General for Translation), alongside other commercial applications. DGT has been using OmegaT for prototyping since 2012, customizing it and extending it with some useful improvements. This information can be useful to endorse the usage of OmegaT. Source: [http://ec.europa.eu/translation/portuguese/magazine/documents/folha54_ot_en.pdf](http://ec.europa.eu/translation/portuguese/magazine/documents/folha54_ot_en.pdf)

OmegaT is also one of the Translator Partners of Microsoft. Please see [https://www.microsoft.com/en-us/translator/business/partners/](https://www.microsoft.com/en-us/translator/business/partners/)
DGT and Microsoft can attest the security of OmegaT.

