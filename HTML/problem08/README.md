## Description

Create an HTML file so it matches the screenshot provided:

![goal](goal.png)

Hint: use the `<table>` element

## Submission

It will automatically be submitted the next time you push.

## Reference

Don't worry about styling and alignment at this point, we'll worry about that when we add CSS

Use `target="_blank"` on the `<a>` tags to open the links in a new tab

Links:

https://en.wikipedia.org/wiki/Canada

https://en.wikipedia.org/wiki/United_States

https://en.wikipedia.org/wiki/China

https://en.wikipedia.org/wiki/Japan

Your file should have this structure:

```
<!DOCTYPE html>
<html>
   <body>
      <h1>Here are some facts about Javascript</h1>
      <table>
         <th>Country</th>
         <th>GDP</th>
         <th>Population</th>
         <th>Area</th>
         <tr>
            <td>Canada</td>
            <td>$1.930 trillion</td>
            <td>37, 242, 571</td>
            <td>9, 984, 670 km2</td>
         </tr>
         <tr>
            <td>United States</td>
            <td>$20.891 trillion</td>
            <td>327, 167, 434</td>
            <td>9, 984, 670 km2</td>
         </tr>
         <tr>
            <td>China</td>
            <td>$27.449 trillion</td>
            <td>1, 403, 500, 365</td>
            <td>9, 596, 961 km2</td>
         </tr>
         <tr>
            <td>Japan</td>
            <td>$5.632 trillion</td>
            <td>126, 440, 000</td>
            <td>377, 973 km2</td>
         </tr>
      </table>
      <h3>Source:</h3>
        <ul>
            <li><a href="https://en.wikipedia.org/wiki/Canada" target="_blank">Canada</a></li>
            <li><a href="https://en.wikipedia.org/wiki/Untited_States" target="_blank">United States</a></li>
            <li><a href="https://en.wikipedia.org/wiki/China" target ="_blank">China</a></li>
            <li><a href="https://en.wikipedia.org/wiki/Japan" target ="_blank">Japan</a></li>
        </ul>
   </body>
</html>
