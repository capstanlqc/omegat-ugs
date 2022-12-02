To ensure that all tags have been inserted correctly:

  * Go to **Tools>Check Issues**. A pop up window will open.

[<img src="/lib/exe/fetch.php?w=200&amp;tok=50dc5e&amp;media=ug:33_check_issues.jpg" class="media" alt="" width="200" />](/lib/exe/detail.php?id=ug%3Aomt-qa-tags&amp;media=ug:33_check_issues.jpg)

By default, other types of checks (Spelling, Terminology, LanguageTool) are ticked. If you want to check for issues related to tags before performing the rest of the checks, you can untick them. You will notice that the **Tag Issues** box cannot be unticked.

  * Press **OK**.
  * An error report will open.

[<img src="/lib/exe/fetch.php?w=300&amp;tok=fb7097&amp;media=ug:34_error_report.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Aomt-qa-tags&amp;media=ug:34_error_report.jpg)

  * Go through the issues one by one:

  1. Correct the issue by clicking on **Jump to Segment**. 
  1. You will arrive at the appropriate segment in the editor pane. 
  1. Place your cursor where the missing tag needs to be inserted and press **Ctrl+T** to insert the missing tag.
  1. Press Enter to move to the next segment.
  1. Open the Error report again. It has automatically refreshed.
  1. Finish going through the issues.

**TIP**: If in the source there are tags that you do not use in your language which are present in the source segment, to avoid having false positives in the error report, you can insert them at the end of the segment. They would not have an impact on any text.

**CAUTION**: Please do not click on "Apply fix", fix each issue manually.
