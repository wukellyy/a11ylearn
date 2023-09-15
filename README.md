# Scavengar hunt! Fix some basic accessibility issues.
This repository contains two pages - one page, called "index," which has very few (hopefully zero) accessibility issues. The other page, called "mistakes," has at least six types of accessibility errors. Please keep in mind that we've organized these errors along the lines of WCAG guidelines, but that usability and accessibility goes beyond a set of rules. It is a fundamental part of your vocation as a dev to continue to explore and learn about what your users need, and to help the internet be useful and enjoyable for everyone.

## Your mission
As a squad, please do the following:
1. Choose a member to fork the repo.
1. Each dev will address two of the issues and investigate them using the resources below.
1. Each dev will open PRs for the issues they've chosen. In your PR, let others know what you learned - be detailed!
1. Review and merge PRs into your fork.

## How to use this code
1. Clone the repo to your computer.
1. If you use an IDE like VSCode (recommended for the cohort), then open the repo and click the "Go live" button in the lower right corner of your IDE.
1. Otherwise, you can open an internet browser, and in the file options, click to open a file. Navigate to one of the HTML files. When you open it, you should see the page.

## Resources
Overview of the success criteria: https://www.w3.org/WAI/WCAG21/Understanding/

1. Missing document language (Understandable)
    1. Resource: [WCAG SC3.1.1](https://www.w3.org/WAI/WCAG21/Understanding/language-of-page)
2. Images without alt text (Perceivable)
    1. Resource: [WCAG SC1.1.1](https://www.w3.org/WAI/WCAG22/Understanding/non-text-content.html), [Alt Text As Poetry](https://alt-text-as-poetry.net/)
3. Insufficient colour contrast (Perceivable) 
    1. Resource: [WCAG SC1.4.3](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum), [WebAIM ContrastChecker](https://webaim.org/resources/contrastchecker/)
4. Links with ambiguous text (Operable)
    1. Resources: [WCAG SC2.4.4](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-in-context), [WCAG Technique F63](https://www.w3.org/WAI/WCAG21/Techniques/failures/F63)
5. Focus outlines (sometimes called focus rings)
    1. Resources: [WCAG SC2.4.7](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible), [WCAG Technique F78](https://www.w3.org/WAI/WCAG21/Techniques/failures/F78)
6. A series of elements which should be a list
    1. Resources: [WCAG SC1.3.1](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships), [WCAG Technique H48](https://www.w3.org/WAI/WCAG21/Techniques/html/H48)