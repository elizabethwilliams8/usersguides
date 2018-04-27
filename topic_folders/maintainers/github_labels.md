### How to label issues

<!-- DO NOT EDIT BY HAND: it should be generated using the carpenter       -->
<!-- R package https://github.com/fmichonneau/carpenter                    -->
<!-- and running:                                                          -->
<!--   carpenter::document_github_labels("data/github_labels.csv")         -->
<!-- the canonical definition of the GitHub labels is stored in the CSV    -->
<!-- file hosted  https://github.com/carpentries/handbook/blob/master/data/github_labels.csv -->

<ul><h3>"status" labels</h3> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #DCECC7; border-radius: 4px; padding: 4px;">help wanted</span>
  <ul>
    <li><b>Hex code:</b> #DCECC7</li>
    <li><b>Short Description:</b> Looking for Contributors </li>
    <li><b>Long Description:</b> Issue reviewed by Maintainers, and ready to be addressed. Maintainers are looking for Contributors to address this issue, anyone is welcome to work on addressing the issue. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #9BCC65; border-radius: 4px; padding: 4px;">status:in progress</span>
  <ul>
    <li><b>Hex code:</b> #9BCC65</li>
    <li><b>Short Description:</b> Contributor working on issue </li>
    <li><b>Long Description:</b> A Contributor is actively working on addressing the issue, this label should be used once someone has been assigned the issue. Because, we can only assign people using GitHub's interface when they are part of the organization, the assignment is done by tagging them in a comment of the issue. The Maintainer should set an initial deadline for a PR to be submitted. We suggest 7 days, but it can be adapted to the discretion of the Maintainer depending on the complexity of the task. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #679F38; border-radius: 4px; padding: 4px;">status:changes requested</span>
  <ul>
    <li><b>Hex code:</b> #679F38</li>
    <li><b>Short Description:</b> Waiting for Contributor to update PR </li>
    <li><b>Long Description:</b> Maintainers have reviewed the pull request, and requested changes. Waiting on the Contributor to implement these changes. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #FFF2DF; border-radius: 4px; padding: 4px;">status:wait</span>
  <ul>
    <li><b>Hex code:</b> #FFF2DF</li>
    <li><b>Short Description:</b> Progress dependent on another issue or conversation </li>
    <li><b>Long Description:</b> Progress on addressing issue or merging PR is dependent on another issue or ongoing conversation and cannot be addressed at this time. Ideally this other conversation should be referenced in the comments. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #FFDFB2; border-radius: 4px; padding: 4px;">status:refer to cac</span>
  <ul>
    <li><b>Hex code:</b> #FFDFB2</li>
    <li><b>Short Description:</b> Curriculum Advisory Committee input needed </li>
    <li><b>Long Description:</b> Maintainers need advice from the Curriculum Advisory Committee to make a decision on how to proceed with the issue or pull request. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #EE6C00; border-radius: 4px; padding: 4px;">status:need more info</span>
  <ul>
    <li><b>Hex code:</b> #EE6C00</li>
    <li><b>Short Description:</b> More information needed </li>
    <li><b>Long Description:</b> Not enough information is provided to proceed with the issue or pull request. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #ffffff; background-color: #E55100; border-radius: 4px; padding: 4px;">status:blocked</span>
  <ul>
    <li><b>Hex code:</b> #E55100</li>
    <li><b>Short Description:</b> Progress on addressing issue blocked </li>
    <li><b>Long Description:</b> A technical problem is hindering progress. A Maintainer or someone else in the community should be notified to ensure that progress is being made. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #EEEEEE; border-radius: 4px; padding: 4px;">status:out of scope</span>
  <ul>
    <li><b>Hex code:</b> #EEEEEE</li>
    <li><b>Short Description:</b> Proposed changes are out of scope </li>
    <li><b>Long Description:</b> Changes proposed in the issue or in the pull request doesn't fall within the scope of the lesson </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #BDBDBD; border-radius: 4px; padding: 4px;">status:duplicate</span>
  <ul>
    <li><b>Hex code:</b> #BDBDBD</li>
    <li><b>Short Description:</b> Issue or PR already exists </li>
    <li><b>Long Description:</b> The concern raised in the issue or pull request has already been mentioned. This previous issues/PR should be mentioned in the comment before this label is used. </li>
 </ul>
</li><h3>"type" labels</h3> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #F8BAD0; border-radius: 4px; padding: 4px;">type:typo text</span>
  <ul>
    <li><b>Hex code:</b> #F8BAD0</li>
    <li><b>Short Description:</b> Typo in text for the lesson, </li>
    <li><b>Long Description:</b> Typo in the text/code of the lesson </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #ffffff; background-color: #EB3F79; border-radius: 4px; padding: 4px;">type:bug</span>
  <ul>
    <li><b>Hex code:</b> #EB3F79</li>
    <li><b>Short Description:</b> Code included in the lesson needs to be fixed </li>
    <li><b>Long Description:</b> Issue about the code, including challenges, answers. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #ffffff; background-color: #AC1357; border-radius: 4px; padding: 4px;">type:formatting</span>
  <ul>
    <li><b>Hex code:</b> #AC1357</li>
    <li><b>Short Description:</b> Formatting needs to be fixed </li>
    <li><b>Long Description:</b> Issue about something being wrong in the formatting of the lesson </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #7985CB; border-radius: 4px; padding: 4px;">type:template and tools</span>
  <ul>
    <li><b>Hex code:</b> #7985CB</li>
    <li><b>Short Description:</b> Issue about template and tools </li>
    <li><b>Long Description:</b> Issue or feature request about a technical aspect of the lesson (e.g., in the scripts used to render the lesson), including the documentation of these tools. Pull requests should probably be directed to https://github.com/carpentries/styles </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #ffffff; background-color: #00887A; border-radius: 4px; padding: 4px;">type:instructor guide</span>
  <ul>
    <li><b>Hex code:</b> #00887A</li>
    <li><b>Short Description:</b> Issue with the instructor guide </li>
    <li><b>Long Description:</b> Issue related to the content of the instructor guide. Best suited to be addressed by someone familiar with the content of the lesson </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #B2E5FC; border-radius: 4px; padding: 4px;">type:discussion</span>
  <ul>
    <li><b>Hex code:</b> #B2E5FC</li>
    <li><b>Short Description:</b> Discussion or feedback about the lesson </li>
    <li><b>Long Description:</b> Issue used to ask a question about how the lesson is taught, ask for clarification. Such issues might indicate that the instructor guide or the documentation may need to be updated. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #7FDEEA; border-radius: 4px; padding: 4px;">type:enhancement</span>
  <ul>
    <li><b>Hex code:</b> #7FDEEA</li>
    <li><b>Short Description:</b> Propose enhancement to the lesson </li>
    <li><b>Long Description:</b> Proposal to add new content to the lesson (e.g., introducing additional function, library, command, flag), or adding more technical detail on a topic already covered in the lesson. Such issues may need to be considered by the infrastructure sub-committee, the curriculum advisory committee, or other relevant group. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #ffffff; background-color: #00ACC0; border-radius: 4px; padding: 4px;">type:clarification</span>
  <ul>
    <li><b>Hex code:</b> #00ACC0</li>
    <li><b>Short Description:</b> Suggest change for make lesson clearer </li>
    <li><b>Long Description:</b> Part of a lesson which, while not incorrect (i.e., not a bug) is presented in a way that is potentially confusing or misleading. Existing content could benefit from rephrasing or rearranging. </li>
 </ul>
</li> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #CED8DC; border-radius: 4px; padding: 4px;">type:teaching example</span>
  <ul>
    <li><b>Hex code:</b> #CED8DC</li>
    <li><b>Short Description:</b> PR showing how lesson was modified in a workshop </li>
    <li><b>Long Description:</b> PR that illustrates how someone modified the lesson in their workshop. Not intended to be merged, but as a way to document how other instructors have used the lesson. Can be closed once the label has been applied. </li>
 </ul>
</li><h3>"difficulty" labels</h3> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #222222; background-color: #FFEB3A; border-radius: 4px; padding: 4px;">good first issue</span>
  <ul>
    <li><b>Hex code:</b> #FFEB3A</li>
    <li><b>Short Description:</b> Good issue for first-time contributors </li>
    <li><b>Long Description:</b> Good issue for a new Contributor to our lesson. </li>
 </ul>
</li><h3>"priority" labels</h3> <li><span style="font-family: monospace; font-weight: bold; font-size: 1.2em; color: #ffffff; background-color: #D22E2E; border-radius: 4px; padding: 4px;">high priority</span>
  <ul>
    <li><b>Hex code:</b> #D22E2E</li>
    <li><b>Short Description:</b> Need to be addressed ASAP </li>
    <li><b>Long Description:</b> For issues and pull requests that needs to be addressed as soon as possible because the lesson uses code that doesn’t work anymore or includes information that is out of date. </li>
 </ul>
</li></ul>
