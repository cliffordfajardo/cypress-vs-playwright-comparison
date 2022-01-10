# Playwright vs Cypress E2E Testing
> Initially this conversation was started in the [Playwright Github Discussions #11201 forum (here)](https://github.com/microsoft/playwright/discussions/11201).


> This comparison table strives to be as accurate and as unbiased as possible. If you use any of these libraries and feel the information could be improved, feel free to suggest changes (with notes or evidence of claims) using the "Edit this page on Github" link at the bottom of this page.

Feature/Capability Key:

- ✅ 1st-class, built-in, and ready to use with no added configuration or code
- 🟡 Supported, but as an unofficial 3rd party or community library/contribution
- 🔶 Supported and documented, but requires extra user-code to implement
- 🛑 Not officially supported or documented.

|                                                    | Playwright [_(Website)_][playwright]      | Cypress [_(Website)_][cypress]      
| -------------------------------------------------- | ----------------------------------------  | ---------------------------           |
| Github Repo / Stars                                | [![][gh-stars-playwright]][gh-playwright] | [![][gh-stars-cypress]][gh-cypress]   |
| Their Comparison                                   |                                           | (none)                                |
| Multiiple Domain Support within same test          | ✅                                        | 🛑                                     |
| Multiiple Browser Tab Support within same test     | ✅                                        | 🛑                                     |
| Multiiple User Support within the same test        | ✅                                        | 🛑                                     |
| Test Block Level Pareallelization                  | ✅                                        | 🛑                                     |
| Test File Level Pareallelization                   | ✅                                        | ✅                                     |
| Test Reporter Customization                        | ✅                                        | ✅                                     |
| Hover Support                                      | ✅                                        | 🔶                                     |
| iFrame Support                                     | ✅                                        | 🔶                                     |
| Breakpoint Debugging Support in IDE                | ✅ (VS Code)                              | 🛑  (need to use debug command)        |
| Speed Rank (Scale 1-5, 5 being fastest)            | 5                                         | 4                                     |
| Free                                               | All Features                              | Subset of features                    |
| Trace Viewer                                       | ✅                                        | ✅                                     |
| Video Recording                                    | ✅                                        | ✅                                     |
| Screenshot capture                                 | ✅                                        | ✅                                     |
| Screenshot diffing                                 | ❔                                        |  ❔                                    |
| Test Retries                                       | ✅                                        | ✅                                     |
| Mobile Emulation                                   | ✅                                        | ✅                                     |
| Geolocation Emulation                              | ✅                                        | 🔶                                     |
| Auto waiting                                       | ✅                                        | ✅                                     |
| Network Monitoring & Interception                  | ✅                                        | ✅                                     |
| API Testing                                        | ✅                                        | ✅                                     |
| Stortybook Support                                 | 🟡                                        | 🟡                                     |
| General Purpose Browser Automation Tool            | ✅                                        | 🛑                                     |

<!-- -->

[playwright]: https://github.com/microsoft/playwright
[bpl-react-query]: https://bundlephobia.com/result?p=react-query
[bp-react-query]: https://badgen.net/bundlephobia/minzip/react-query?label=💾
[bp-playwright]: https://badgen.net/bundlephobia/minzip/playrwright?label=💾
[gh-playwright]: https://github.com/microsoft/playwright
[gh-stars-playwright]: https://img.shields.io/github/stars/microsoft/playwright?label=%F0%9F%8C%9F

<!-- -->

[cypress]: https://github.com/cypress-io/cypress
[bp-cypress]: https://badgen.net/bundlephobia/minzip/playwright?label=💾
[gh-cypress]: https://github.com/cypress-io/cypress
[gh-stars-cypress]: https://img.shields.io/github/stars/cypress-io/cypress?label=%F0%9F%8C%9F
[bpl-cypress]: https://bundlephobia.com/result?p=cypress




References
- https://playwright.dev/
- https://docs.cypress.io/
- https://blog.checklyhq.com/cypress-vs-selenium-vs-playwright-vs-puppeteer-speed-comparison/
- https://blog.logrocket.com/playwright-vs-puppeteer/
- https://storybook.js.org/addons/storybook-addon-playwright
- https://www.cypress.io/blog/2021/05/19/cypress-x-storybook-2-0/
- https://docs.cypress.io/guides/references/trade-offs#Permanent-trade-offs-1
- https://cathalmacdonnacha.com/cypress-vs-playwright-which-is-best-for-e2e-testing
- https://www.npmjs.com/package/playwright-testing-library
- https://playwright.dev/docs/emulation#geolocation
- https://github.com/cypress-io/cypress/issues/2671
- https://github.com/tomByrer/codecept-playwright-vs-cypressio-fb/blob/master/article.md

