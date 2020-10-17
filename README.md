# GradeCalculator

The code is in `index.html`. Whenever the `main` branch gets updated, the site is deployed at <https://focused-kowalevski-932dc5.netlify.app/>.

Things to try:

- Make it say "Your final grade is 80%" instead of just "80"
- Show letter grades (A, B, C, D, F) in addition to numerical grades (Look up `if`, `else if`, and `else` in JavaScript)
- Make each label and input appear on its own line
- Given the 1st and 2nd quarter grades and the grade you want, calculate what grade you need to get on the exam
- Make it recalculate the output every time the inputs change without using the submit button
- Make stuff look better with CSS styling
  - You could try out some classless CSS frameworks by adding this line:
    ```html
    <script
      src="https://dohliam.github.io/dropin-minimal-css/switcher.js"
      type="text/javascript"
    ></script>
    ```
- In our JavaScript code, we referred to "quarter1", "quarter2", "examGrade", and "form" directly.
  This works, but it's considered a bad idea because it's hard to keep track of where your variables are coming from.
  Google "document.getElementById" and use that to get access to our HTML elements instead of referring to them directly.

When you've made an improvement, feel free to make a pull request.
