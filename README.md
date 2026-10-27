# Excel skill recorder practice

Practice files for Stringfest Analytics' hands-on review of the skill recorder in Copilot for Excel.

1. Open `skill-recorder-practice.xlsx` in Excel with Copilot workbook editing and **Record a skill** available.
2. Open Copilot, select **+ > Record a skill**, and wait until recording is active.
3. Use `practice-prompts.txt` to add the demonstration columns, explain the rules, and test the saved skill.

The workbook contains six fictional orders in `tblOrders` on `Orders`, including cancelled quantities. All quantities are units. Enter `=[@Ordered]-[@Shipped]-[@Cancelled]` once in the new Open units table column. Excel fills the calculated column. The first results should be 30, 0, 40, 60, 20, 0 (150 total).

After recording, change D8 to 60 and F8 to `Complete.`. The formula should recalculate to zero; the written question is a snapshot until you rerun the skill. The new open-unit total is 90. Birch is also complete: 80 ordered minus 70 shipped minus 10 cancelled equals zero.

The recorder drafts your own skill; its name, files, wording and availability may differ. Review the proposed instructions and any generated code before saving. No prebuilt skill is included because creating it is the exercise.

The workbook uses no VBA macros and requires no local Python installation. A Microsoft account with access to the recorder is needed for the full exercise; the download itself needs no GitHub account.

An exercise by George Mount, Stringfest Analytics: https://stringfestanalytics.com/
