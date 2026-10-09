# Accessibility Audit Report

## Website Audited

My personal portfolio website: Brian Njuguna.

## Tool Used

Google Chrome Lighthouse.

## Checks Performed

I used Lighthouse to inspect accessibility and common website quality checks.

## Accessibility Findings

1. **Image alternative text:** My image has an `alt` attribute. I should use descriptive text that explains the image.
2. **Heading structure:** The page has an `<h1>` heading followed by `<h2>` headings for its sections.
3. **Descriptive links:** The page includes a link to GitHub and an email link.
4. **Language attribute:** The HTML document uses `lang="en"`.
5. **Page title:** The page has a descriptive title in the `<title>` element.
6. **Keyboard navigation:** Lighthouse includes checks for keyboard focus and logical navigation. These should also be tested manually.

## Issues and Improvements

* Replace the placeholder image with a relevant personal image and descriptive alternative text.
* Add semantic landmarks such as `<main>` to improve page navigation.
* Add a meta description to summarize the website.
* Test keyboard navigation by using the Tab key.

## Conclusion

Lighthouse helped me understand how accessibility checks can identify ways to make a website easier to use. Automated testing does not detect every accessibility issue, so manual testing is also important.
