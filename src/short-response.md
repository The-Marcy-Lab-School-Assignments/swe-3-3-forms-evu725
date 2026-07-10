# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**
Accessibility is creating digital experiences to the needs of all users, including those with disabilities. It is important because it helps people with different abilities easily find the information they need without becoming overwhelmed or having to spend extra time navigating website components.

Labels make form inputs more accessible by telling users what information is expected in each field. They also make forms easier to use by allowing users to click the label text to select or focus the input.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**
- The `for` attribute is used on a `<label>` element. It connects the label to an input by matching the label's `for` value with the input's `id`. This allows users to click the label to focus on the input and helps assistive technologies identify the correct label for each field.
- The `name` attribute identifies the input when the form is submitted. It tells the server which field the submitted value belongs to.
- The `id` attribute provides a unique identifier for an HTML element. It is used by the label's for attribute to link the label to the correct input field.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**
Using specific input types like `type="email"` or `type="number"` is better than using `type="text"` because they define what type of information the input expects, helping users enter the correct data format.

The advantages they provide include built-in browser validation to check for incorrect input and helping users with assistive technologies better understand what information should be entered. They also provide a better user experience through features like mobile keyboards that match the type of information being entered and give clearer meaning to browsers and developers.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**
An example of a real web application that uses a form is **Google Forms Survey**. When surveyors submit a form, the application collects all responses and puts them into a spreadsheet. This allows the creator of the form to easily access and analyze the data.