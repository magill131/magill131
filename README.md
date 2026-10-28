# Chris Magill

**Quality Assurance Engineer | Mobile, Web & API Testing | AI-Assisted Testing with Claude Code | Nashville, TN**

Test Automation | Web, iOS & Android

Over 3 years in QA I have covered iOS, Android and web across Dev, QA, Staging and Production. At IDEXX I built a Claude Code tool that cut a recurring testing task from about 60 minutes to under 15.

The repositories here are test frameworks I built to practice that work: UI, API, performance, accessibility, contract and AI-assistant testing. Most of them run in CI on GitHub Actions.

## Tech stack

| | |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, SQL |
| **Frameworks** | Selenium, Playwright, Cypress, pytest, Behave, Hypothesis |
| **Tools** | Postman, JMeter, Docker, GitHub Actions, Jira, TestRail, LambdaTest, TestRigor, Datadog, LaunchDarkly, axe-core, Claude Code |

## Featured projects

**[saucedemo-selenium-pytest-framework](https://github.com/magill131/saucedemo-selenium-pytest-framework)**  
UI test framework for saucedemo.com: Python, Selenium and pytest with a Page Object Model, run in CI on GitHub Actions.  
17 tests across login, inventory, cart and checkout, tagged smoke or regression. Failures save a screenshot, and every CI run uploads an HTML report.

**[ai-assisted-test-generation](https://github.com/magill131/ai-assisted-test-generation)**  
AI-assisted test generation with Claude Code: user stories to test cases to Playwright tests, with every AI mistake logged.  
Nine user stories became 31 reviewed test cases and 31 Playwright tests. A person reviews each step, and the AI's mistakes are written down in a review log.

**[ai-assistant-evaluation-tests](https://github.com/magill131/ai-assistant-evaluation-tests)**  
Automated quality checks for an AI assistant's answers: grounding, citations, refusals, consistency and golden questions, with a CI quality gate (pytest, GitHub Actions).  
Three deliberately broken assistants must each fail the checks, and the tests caught a real ranking defect while I built it.

**[wage-compliance-property-tests](https://github.com/magill131/wage-compliance-property-tests)**  
Property-based tests (Hypothesis + pytest) for a wage compliance rules engine, with a rule traceability matrix and a CI quality gate on GitHub Actions.  
I broke the engine three ways on purpose and the tests caught each one. A CI gate fails if any rule has no tests.

All 16 projects are listed at [magill131.github.io](https://magill131.github.io).

## Find me

- LinkedIn: [linkedin.com/in/chris-magill](https://www.linkedin.com/in/chris-magill)
- Website: [magill131.github.io](https://magill131.github.io)
- Email: [magill.chris91@gmail.com](mailto:magill.chris91@gmail.com)
