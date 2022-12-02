# OmegaT - Translation guide

**OmegaT** is the open source computer-assisted translation tool (CAT tool) which will be used to translate, reconcile, adapt, review and verify materials. The software has been customized to enable you to perform your task. 

## Installation and setup

To install OmegaT on a computer running on Windows, please consult the .

## Accessing the package

### Accessing the package for the first time

The following steps need to be performed __only once per OmegaT package__: when you access each package for the first time: 

1. Download the  from the portal

2. Store the  in a location you will remember on your computer. 

3. Import the  in OmegaT: 

  * Open OmegaT
  * Go to **Project>Import OMT package**

[<img src="/lib/exe/fetch.php?w=400&amp;tok=6dfa55&amp;media=ug:01_import_omt_package.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:01_import_omt_package.jpg)

  * Navigate to the location where you stored the OMT package. Choose the  and click on Open

[<img src="/lib/exe/fetch.php?w=400&amp;tok=c05e5c&amp;media=ug:02_open_omt_package.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:02_open_omt_package.jpg)

  * A pop up opens. Click **Yes**.

[<img src="/lib/exe/fetch.php?w=400&amp;tok=b68ae1&amp;media=ug:03_delete_original_package.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:03_delete_original_package.jpg) 

4. Translate/Reconcile/Adapt/Review the files in the package.

When you are done working for the day, close OmegaT.

### Access the package after import

The next times you want to access the project in OmegaT, go to **Project>Open Recent Project**. The project you were working on is the first one in the list:

[<img src="/lib/exe/fetch.php?w=500&amp;tok=975b56&amp;media=ug:04_open_recent_project.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:04_open_recent_project.jpg)

## Navigation

### Navigation between the different panes

When you open OmegaT you will notice the screen is split in several panes:

  * The **Editor pane** is the main pane in which you will be working.
  * Translation suggestions will appear in the **Fuzzy Matches pane**.
  * The **Glossary pane** will display the existing glossary entries and the ones you may add.
  * The **Multiple Translations pane** will show you if a repeated segment was translated differently.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=d1fed0&amp;media=ug:05_omegat_panes.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:05_omegat_panes.jpg)

### Navigation between the different files

If the project contains multiple files, they are listed in the **Project Files pane**. The file currently open is highlighted in blue.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=626b40&amp;media=ug:06_project_files_pane.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:06_project_files_pane.jpg)

If you want to open a different file in the Editor pane, click on it in the Project Files pane. You can also see the name of the file that is open in the Editor pane's title bar.

### Navigation between segments

In the editor pane, the active segment is highlighted in green. This is the segment you are working in. When you type or insert a translation, it will appear **below the source text**. 

Press the **Enter** key on your keyboard to go to the next segment. You can also use **Ctrl+U** to jump to the next untranslated segment.
A segment can also be activated by double clicking on it. It then becomes green.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=f35847&amp;media=ug:07_active_segment.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:07_active_segment.jpg)

In OmegaT, a **color code** will help you find your way around between the different segments:

  * **Green** = the segment you are working in (active segment)
  * **Blue** = untranslated segment
  * **Grey** = translated segment. The translation is displayed below the source text.
  * **Orange** = pretranslated and locked segment (e.g. trend). If you want to make a change to a trend segment, document it in the Excel Sheet but do not try to change it in OmegaT. Any changes you make to these segments will not be saved. The existing translation will be maintained.

[<img src="/lib/exe/fetch.php?w=600&amp;tok=3087d8&amp;media=ug:08_color_coding.jpg" class="media" alt="" width="600" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:08_color_coding.jpg)

## Handling tags (Ctrl+T)

### Recognizing tags

If you are in a segment which contains tags, you will recognize them because they are in **red font**. 
[<img src="/lib/exe/fetch.php?w=500&amp;tok=04ce0a&amp;media=ug:09_tags_recognizing.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:09_tags_recognizing.jpg)

There are two types of tags - standalone tags and double tags:

  * **Standalone tags** = a single tag with a precise role (e.g. <br/> tag which introduces a new paragraph in HTML)
  * **Double tags** are composed of an opening and a closing tag, such as the HTML tags for making text bold, italic, underlined, etc. **Double tags** affect the text between them and you need to ensure they are positioned around the exact same words in the source and in the translation.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=134d2a&amp;media=ug:10_types_of_tags.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:10_types_of_tags.jpg)

### Inserting tags

To insert tags in your translation, you should use the keyboard shortcut **Ctrl+T**, which inserts the next missing tag.

Please note that tags are inserted in the order of their appearance in the source segment. If you need to insert tags in a different order than in the source, we advise you to translate the entire segment, place your cursor where the first tag has to be inserted and press Ctrl+T, then repeat the operation until all tags have been inserted.
[<img src="/lib/exe/fetch.php?media=ug:11_tag_order.jpg" class="media" alt="" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:11_tag_order.jpg)

If you have inserted a tag incorrectly and need to **delete** it, **select the tag** in full (you can **double click** on it) and press **backspace** or delete on your keyboard.

### Most common HTML tags

Below you will find the most common HTML tags you may encounter.

[<img src="/lib/exe/fetch.php?w=400&amp;tok=d168ca&amp;media=ug:11_b_tags_html.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:11_b_tags_html.jpg)

## Using Fuzzy matches (Ctrl+I)

When you translate, your translations are saved in the project’s translation memory. When you activate a segment which is similar to one you have already translated, you will see suggestions appearing in the fuzzy matches pane. 

The source in the fuzzy matches pane shows the difference between the active segment and the previous translation in “track changes” mode like in Word:

  * Parts that do not appear in the active segment are in ~~~~
  * Parts that are added are in ____

[<img src="/lib/exe/fetch.php?w=400&amp;tok=e3aa6f&amp;media=ug:12_fuzzy_matches.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:12_fuzzy_matches.jpg)

When there are several fuzzy matches for a segment, they are sorted by similarity to the new segment. The active fuzzy match is the one in **bold**. By default, it will be the first one in the list. If you want to use a different fuzzy match, **double click** on it to activate it. 

[<img src="/lib/exe/fetch.php?w=600&amp;tok=e193fb&amp;media=ug:13_selected_fuzzy.jpg" class="media" alt="" width="600" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:13_selected_fuzzy.jpg)

To insert the fuzzy match in full, press **Ctrl+I** on your keyboard. After inserting it, do not forget to make the necessary changes so that it fits the segment you are translating.

Alternatively, you can also insert only a part of the fuzzy match or combine several matches:

  * Activate the match you want use
  * With your mouse, select the part you wish to insert
  * Press **Ctrl+I** on your keyboard to insert it 
  * Select another fuzzy match if appropriate or finish translating the segment

[<img src="/lib/exe/fetch.php?media=ug:14_select_part_fuzzy.jpg" class="media" alt="" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:14_select_part_fuzzy.jpg)

## Using the Glossary

OmegaT supports glossaries. Your package may already contain a glossary with key terms, but you can also add terms to the glossary yourself.

### Inserting glossary terms

When you arrive in an active segment which contains a glossary term, the respective term is underlined in blue in the source segment. 
You will see the suggested target term in the **Glossary pane**, on the right.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=4c9a4d&amp;media=ug:20_glossary_term.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:20_glossary_term.jpg)

OmegaT has **predictive typing**: when you start typing the first character of the target term in the glossary, the auto-completer will suggest the term. To insert it, press **Enter** on your keyboard.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=b4d4c2&amp;media=ug:21_predictive_typing.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:21_predictive_typing.jpg)

### Adding terms to the glossary

If the project you are working on contains technical terms or you notice certain terms keep repeating, you can add them to the glossary. To add a term:

  * In the active segment,** select the term** you want to insert with your mouse
  * **Right click** and choose **Add glossary entry** from the contextual menu

[<img src="/lib/exe/fetch.php?w=400&amp;tok=2d8673&amp;media=ug:22_add_glossary_entry.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:22_add_glossary_entry.jpg)

  * A pop-up window will open
  * Enter the Target term and press the **OK** button.

[<img src="/lib/exe/fetch.php?w=300&amp;tok=d8fbd6&amp;media=ug:23_glossary_term.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:23_glossary_term.jpg)

## Handling repeated segments

Some segments are identical. They are called “**repeated segments**” and their translation is __autopropagated__. 

### Identifying repeated segments

You can recognize that you are in a repeated segment because it has gray font.
When a repeated segment is active, the segment number will indicate how many repetitions exist: 

[<img src="/lib/exe/fetch.php?w=400&amp;tok=605c86&amp;media=ug:15_repeated_segment.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:15_repeated_segment.jpg)

If you **right click** on a repeated segment, the contextual menu will point out the other occurrences of a repeated segment. It can be useful to jump to them (by selecting them from the contextual menu) to see the different contexts in which a repeated segment appears.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=596504&amp;media=ug:16_repeated_context.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:16_repeated_context.jpg)

### Autopropagation

If you edit the translation of a repeated segment, by default, the changes will be automatically reflected in all the repetitions. This happens in the same file, but also in all the files of the OmegaT package.

[<img src="/lib/exe/fetch.php?w=400&amp;tok=006fba&amp;media=ug:17_autopropagation.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:17_autopropagation.jpg)

### Create alternative translation

In some cases, you may not wish to modify the translation of all repeated segments. Due to a different context, you may need to change only ONE of the repeated segments:

  * **Right click** on the segment 
  * Choose **Create Alternative Translation** from the contextual menu

[<img src="/lib/exe/fetch.php?w=400&amp;tok=1dfcc4&amp;media=ug:18_create_alternative_translation.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:18_create_alternative_translation.jpg)

  * Change the translation of your active segment and then either press **Ctrl+S** or move to the next one.

[<img src="/lib/exe/fetch.php?w=800&amp;tok=500141&amp;media=ug:19_alternative_translation_created.jpg" class="media" alt="" width="800" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:19_alternative_translation_created.jpg)

If you return on the repeated segment, you will see the different translations appear in the Multiple Translations pane.

## Other useful features

### Inserting source segment in target

In some cases, the translation and the source segment must be identical. To insert the source text in the target segment, press **Ctrl+Shift+S** on your keyboard.
[<img src="/lib/exe/fetch.php?w=400&amp;tok=826218&amp;media=ug:24_identical_source.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:24_identical_source.jpg)

You can also copy & paste the source text into the target.

### Leaving a segment empty

All segments of the OmegaT package must have a translation. If you leave a segment empty, the source text will be displayed in the final document. If you wish the segment to remain empty, **insert a space** in the target segment instead of the actual translation.

### Using the character table

**Special characters** can be inserted with the Special Characters Table. Special characters can be:

  * quotation marks: «», „“, ‘’, etc. 
  * mathematical symbols: ×, π, ÷, ≤, ≠, √, etc. 
  * other characters: ®, ™

When you arrive in a segment in which you need to insert a special character, perform the following steps:

  * Press **Ctrl+Space** on your keyboard several times until you reach the special characters table.

[<img src="/lib/exe/fetch.php?w=400&amp;tok=ce65e0&amp;media=ug:25_character_table.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:25_character_table.jpg)

  * Select the character you want to insert
  * Press **Enter** and continue editing your segment.

[<img src="/lib/exe/fetch.php?w=300&amp;tok=0bb88d&amp;media=ug:26_inserted_special_characters.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:26_inserted_special_characters.jpg)

### Inserting non-breaking spaces

In order to insert non-breaking spaces in OmegaT, please make sure you have installed **Auto Hot Key**. If you haven't installed it yet, please check the **Third Party Tools** section of the [OmegaT Installation guide](/doku.php?id=ug:tec-cb-ome-ins)

Once **Auto Hot Key** is installed, you can insert non-breaking spaces with the same keyboard shortcut as in Word: **Ctrl+Shift+Space**. You can recognize a non breaking space because it is gray. 

[<img src="/lib/exe/fetch.php?w=300&amp;tok=bdb050&amp;media=ug:27_non-breaking_spaces.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:27_non-breaking_spaces.jpg)

### Performing concordance searches (Ctrl+F)

A concordance search allows you to look for words and expressions in the translation memory and the glossary. To perform a search follow the steps below:

  * In the active segment, select the word you want to search for with your mouse.
  * Press **Ctrl+F** on your keyboard.
  * The Search window will open.
  * Press Search. 
  * The results will be displayed.
  * You can copy (select with mouse and press Ctrl+C on your keyboard) what you need from the results and paste it in the target translation at the right place.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=fffd03&amp;media=ug:38_concordance_search.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:38_concordance_search.jpg)

**TIP:** There might be small differences (in punctuation, spacing, etc.) between the text you're searching for and other occurrences of the same text that would prevent an *exact match*. The option "Keyword search" might help overcome that problem, please use it if you don't get the results you were expecting.

## Performing QA checks in OmegaT

### Completion check

All segments of the OmegaT package must have a translation. To ensure that is the case, please check for completion prior to delivery:

  * Go to **Project>Project Files**
  * The project files pane will open
  * **OK:** If the **Number of unique segments** __is equal to__ the number of **Translated unique segments**.

[<img src="/lib/exe/fetch.php?w=500&amp;tok=7c8254&amp;media=ug:32_completion.jpg" class="media" alt="" width="500" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:32_completion.jpg)

  * **NOT OK**: the **Number of unique segments** __is different from__ the number of **Translated unique segments**. To correct: 

  1. Close the Project Files Pane
  1. Press **Ctrl+U** on your keyboard to jump to the __Next Untranslated Segment__. 
  1. When the cursor stops moving from the active segment then all segments have a translation.

Recheck for completion, to make sure by opening the Project Files pane.

### Check and fix tags

To ensure that all tags have been inserted correctly:

  * Go to **Tools>Check Issues**. A pop up window will open.

[<img src="/lib/exe/fetch.php?w=200&amp;tok=50dc5e&amp;media=ug:33_check_issues.jpg" class="media" alt="" width="200" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:33_check_issues.jpg)

By default, other types of checks (Spelling, Terminology, LanguageTool) are ticked. If you want to check for issues related to tags before performing the rest of the checks, you can untick them. You will notice that the **Tag Issues** box cannot be unticked.

  * Press **OK**.
  * An error report will open.

[<img src="/lib/exe/fetch.php?w=300&amp;tok=fb7097&amp;media=ug:34_error_report.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:34_error_report.jpg)

  * Go through the issues one by one:

  1. Correct the issue by clicking on **Jump to Segment**. 
  1. You will arrive at the appropriate segment in the editor pane. 
  1. Place your cursor where the missing tag needs to be inserted and press **Ctrl+T** to insert the missing tag.
  1. Press Enter to move to the next segment.
  1. Open the Error report again. It has automatically refreshed.
  1. Finish going through the issues.

**TIP**: If in the source there are tags that you do not use in your language which are present in the source segment, to avoid having false positives in the error report, you can insert them at the end of the segment. They would not have an impact on any text.

**CAUTION**: Please do not click on "Apply fix", fix each issue manually.

### Check glossary adherence

You can check whether the translation adheres to the glossary and key terms have been translated consistently throughout:

  * Go to **Tools>Check Issues**
  * Make sure the box next to **Terminology Issues** is ticked

[<img src="/lib/exe/fetch.php?w=200&amp;tok=fc754b&amp;media=ug:35_terminology_issues.jpg" class="media" alt="" width="200" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:35_terminology_issues.jpg)

  * Press** OK.** 
  * An error report will open

[<img src="/lib/exe/fetch.php?w=600&amp;tok=589156&amp;media=ug:36_error_report_terminology.jpg" class="media" alt="" width="600" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:36_error_report_terminology.jpg)

  * Go through the issues one by one and jump to segment to correct the potential error if needed.

**TIP**: Not all flagged issues are errors by default. In some cases, you may get false positives. In the screenshot below, "apple trees" should be translated as "pommiers" as in the first segment. In the second segment (active segment) "apple trees" was rendered as "ces arbres" (backtranslation: these trees) to avoid a repetition that would be disturbing in French. Such deviations from the glossary are intentional.

[<img src="/lib/exe/fetch.php?w=800&amp;tok=010cc1&amp;media=ug:37_false_positive.jpg" class="media" alt="" width="800" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:37_false_positive.jpg)

## Creating target files

Press **Ctrl+Shift+D** to create the target file you were working on. This will allow you to preview the translated file with your changes.

To access the file, go to **Project>Access Project Contents>Target Files**. A window with the contents of the "target" folder will open. Find the file you were working on, if there are several files and preview it to read the translation in context.

[<img src="/lib/exe/fetch.php?w=300&amp;tok=75f3dc&amp;media=ug:28_target_files.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:28_target_files.jpg)

## Delivering the project

Once you have finished editing the OmegaT package and have performed the appropriate Q&A checks, you need to Export the .

  * Go to **Project>Export OMT Package**

[<img src="/lib/exe/fetch.php?w=300&amp;tok=f24532&amp;media=ug:29_export_omt.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:29_export_omt.jpg)

  * A pop up window will open.
  * Click Save
  * Press OK in the Pop-up window notifying that the package was successfully created.

[<img src="/lib/exe/fetch.php?w=300&amp;tok=f25354&amp;media=ug:30_omt_successful.jpg" class="media" alt="" width="300" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:30_omt_successful.jpg)

  * You will be automatically directed to the location the exported package is stored.
  * You will recognize the package because it has the extension OMT. It should be the 4th from the bottom.

[<img src="/lib/exe/fetch.php?w=400&amp;tok=5c3807&amp;media=ug:31_recognizing_omt.jpg" class="media" alt="" width="400" />](/lib/exe/detail.php?id=ug%3Atec-cb-ome-tra&amp;media=ug:31_recognizing_omt.jpg)

This is the file you have to deliver.

## Shortcuts cheatsheet

Here is a table summarizing all functions you need to remember to work in OmegaT. Shortcuts (keyboard combinations) are provided if they are frequently used.
 Shortcut         | Menu/Action                                       | Function                                                     
| **Ctrl+L**        | Project > Project Files                           | Open the Project Files window                                
| **Ctrl+J**        | Go To > Segment Number…                         | Go to the segment thus numbered                              
| **Ctrl+Space**    | N/A                                               | Press several times to open Character table                  
| **Ctrl+U**        | Go To > Next Untranslated Segment                 | Go to the next untranslated segment                          
| **Ctrl+T**        | Edit > Insert Next Missing Tag                    | Insert the next missing tag                                  
| **Enter**         |                                                   | Go to Next Segment                                           
| **Ctrl+I**        |                                                   | Insert active fuzzy match or selection of fuzzy match        
|                   | **Right click > Create Alternative Translation**  | Mark a segment as alternative translation                    
| **Ctrl+Shift+S**  |                                                   | Mark a segment as a translation identical to the source      
| **Ctrl+Shift+V**      | Tools > Check issues                              | Run the QA checks                                            
| **Ctrl+Shift+D**      | Project > Create Current Translated Document      | Export or generate the target file for the current document  
| **Ctrl+D**            | Project > Create Translated Documents             | Export or generate all target files                          
|                   | **Project > Access Project Contents > …**       | Go to the project folders                                    
| **Shift+F3**          |                                                   | Change capitalization of selected text                       

