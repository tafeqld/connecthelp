---
title: "Gradebook basics"
description: ""
lead: ""
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "assess_grade"
weight: 100
toc: true
---

 A grade book contains your grading system, grade calculations, grade scheme, grade items, and view and display options. Grade items in your grade book represent all the work that you want to evaluate users on in a unit. You can evaluate specific tasks such as assignments, tests, and participation, and you can also create grade items and associate them with unit objects such as Dropbox and Quizzes.

You must set up a grade book before you can use the Grades tool. As you plan your grade book, consider:

- What grade items you plan to evaluate.
- Which grading system is most appropriate for your unit.
- How you will allocate points or weights across grade items.
- Which grade items you want to associate with unit objects.
- If you want to include a milestone grade at least once during the unit.
- How you want to calculate final grades.

NOTE Making changes to a grade book's settings and calculation options after you begin tracking users' grades can significantly affect existing data. 

### Grading concepts

<table>
  <tr>
    <th>Concept</th>
    <th>Description</th> 
  </tr>
  <tr>
    <td>Gradebook</td>
    <td> 	
A grade book contains your grading system, grade calculations, grade scheme, grade items, and view and display options. Grade items in your grade book represent all the work that you want to evaluate users on in a unit. You can evaluate specific tasks such as assignments, tests, and participation, and you can also create grade items and associate them with unit objects such as assignment submission folders and quizzes.

You must set up a grade book before you can use the Grades tool. As you plan your grade book, consider:

- Which grade items you plan to evaluate.
- Which grading system is most appropriate for your unit.
- How you will allocate points or weights across grade items.
- Which grade items you want to associate with unit objects. Note that only numeric grade items can be associated with unit objects.
- If you want to include a milestone grade at least once during the unit.
- How you want to calculate final grades.

Making changes to a grade book's settings and calculation options after you begin tracking users' grades can significantly affect existing data.
</td> 
  </tr>
  <tr>
    <td>Grading system</td>
 <td> 
The grading system determines how the grade items in your grade book contribute to users’ final grades. There are three options:

- Grade items can count as a percentage of a final grade worth 100%.
- Grade items can be worth a certain amount of points that are totaled for a final grade.
- You can define a custom formula for how grade items contribute to a final grade.

Typically, this setting has been pre-configured for educators when your unit is populated with learning material and assessments.
</td> 
  </tr>
<tr>
    <td>Grade items</td>
 <td> 
Grade items in your grade book represent all the work that you want to evaluate users on in a unit. Grade items can exist independently in your grade book, or you can associate numeric grade items with unit objects such as discussions, quizzes, and assignment submission folders. Each grade item has an entry in the grade book, which you assign a grade to for each user. Depending on the grade item type you want to create, grade items can be graded numerically or based on a grade scheme.

Typically, these grade items have been pre-configured for educators when your unit is populated with learning material and assessments. 
</td> 
</tr>
<tr>
    <td>Calculated final grade</td>
 <td> 
The final grade calculated by the grade book. You cannot adjust the final grade without adjusting grade item scores. 
</td> 
</tr>
<tr>
    <td>Adjusted final grade </td>
 <td> 
You can manually change the final grade calculation without affecting grade item scores. 
</td> 
</tr>
</table>

### Grading schemes

A grade scheme enables you to organise users’ performances on grade items into levels of achievement. A grade scheme can include any number of achievement levels. Each achievement level has its own range of acceptable grades and a symbol, such as a numeric value, letter, or text description, to represent it. It is highly recommended to use the grade schemes set up by TAFE Queensland, but it is possible to also create your own custom grade schemes. 

<table>
  <tr>
    <th>Grade Scheme</th>
    <th>Example</th> 
  </tr>
  <tr>
    <td>Letter</td>
    <td> 	
F, P, C, D, HD 
  </td> 
  </tr>
  <tr>
    <td>Numeric</td>
    <td> 	
2.0, 2.5, 3.0, 3.5, 4.0 
  </td> 
  </tr>
<tr>
    <td>Text</td>
    <td> 	
Not Graded, Satisfactory, Unsatisfactory 
  </td> 
  </tr>
</table> 

### Create a grade scheme

To create a grade scheme

```bash
1. On the navbar, click Grades.
2. On the Schemes page, click New Scheme.
3. In the General area, enter the scheme Name.
4. In the Ranges area, enter your scheme details. If you do not assign a value in the Assigned Value % field, the Start % is used as the default.
5. To add more levels to your scheme, click The Add iconAdd Ranges.
6. Click Save and Close.
```


## Grading systems

Selecting a grading system is the first step in setting up your grade book. 

| System   | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |   |   |   |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|---|---|
| Weighted | The weighted system calculates grade items as a percentage of a final grade worth 100%. The maximum points you assign to individual grade items can be any value, but their contribution towards the category they belong to and the final grade is the percentage value (weight) assigned to them. Grade items in a category count as a percentage of that category, not of the final grade. Therefore, grade items in a category should combine to a weight of 100%. For example, if you have a category worth 10% of the final grade with two equally weighted grade items, the weight of each grade item is 50%, (its contribution to the category), not 5% (its contribution to the final grade). Since it's a category’s weight and not an individual grade item’s weight that counts toward the final grade, the final grade is inaccurate until all the items in the category are graded. If you want to release final grades to users before all the items are graded, you can drop ungraded items from the calculation until the end of the unit when you want all grade items to be considered. Otherwise, the final grades might be misleading. If your grade items do not add up to 100%, you will receive a warning message. You can ignore this message if you choose; a balanced grade book is not required. If the weights assigned to grade items do not sum to 100%, the tool adjusts the weight of each item. For example, if you have three grade items with a weight of 25% each, each item is actually calculated as 33%. This is true for categories and the final grade. |   |   |   |
| Points   | Use the points system when you want the maximum points assigned to a grade item to be equal to its contribution to the final grade. Final grades are calculated by adding a user’s score on all grade items together and dividing by the sum of the maximum points values. The sum of the maximum points values for all grade items does not need to equal 100. With the points system you do not specify a category’s weight or total points. It is the maximum points assigned to an individual grade item that counts toward the final grade. Make sure the maximum points assigned to grade items reflect how much you want them to be worth. For example, don’t grade each of your 20 homework assignments out of 50 points and then your final exam out of 80 points. Another option in the point system is to exclude an item from the final grade calculation. This enables you to evaluate a grade category, numeric grade item, selectbox grade item, or pass/fail grade item without including the grade in users’ calculated or adjusted final grades. The New/Edit Item page and the New/Edit Category page both include an Exclude from Final Grade Calculation check box. You can achieve similar functionality in the weighted system by setting the grade item or category’s weight to 0%. Note: At the time of writing, Points is the most common grading system in use at TAFE Queensland for competency-based units.                                                                                                                                                          |   |   |   |
| Formula  | Use the formula system when you want to calculate final grades using a custom formula that allows for conditions. The formula system is based on the points system, but allows you to set conditions around grade items to determine the final grade. For example, you could require that users receive at least 50% on their midterm and final exam to pass a unit. The formula system might not be available at your organisation. If you do not have this option, you can release the adjusted final grade and calculate your custom formula manually, or you can contact your site administration about getting access to this functionality. Note: At the time of writing, using a Formula is the best way to get an accurate unit level-final grade (e.g. J or M) at TAFE Queensland for competency-based units.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |   |   |   |

