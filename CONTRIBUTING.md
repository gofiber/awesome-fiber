# Contribution Guidelines

> Please be aware that we want to accept your contribution, but we have **some rules to keep the minimum quality** of the packages listed here. All reviews are **not personal feedback**, even if you are a _developer reviewing your contribution_. **Sorry if we can't meet your expectations, we do our best**.

Please note that this project follows the [Fiber code of conduct](https://github.com/gofiber/.github/blob/main/CODE_OF_CONDUCT.md). By participating you agree to abide by its terms.

- **To add, remove, or change things on the list:** Submit a pull request

- List items should be sorted _alphabetically_;
- Each item should be limited to one link;
- The link should be the name of the package or project;
- Descriptions should be clear, concise, and non-promotional;
- Descriptions should follow the link, on the same line and end with a punctuation mark;
- At least 3 items are needed to create a new category;
- The package or project had to be maintained under **open source license** ( _we make a brief review of the code before the link enters the list_ ), [see list of allowed licenses](https://opensource.org/licenses/alphabetical);
- Remember to put a period `.` at end of the project description.

Please contribute links to packages/projects you have used or are familiar with. This will help ensure high-quality entries.

The Core and Contrib sections are not maintained by hand alone: a weekly workflow compares them against the middlewares that actually exist in [gofiber/fiber](https://github.com/gofiber/fiber/tree/main/middleware) and [gofiber/contrib](https://github.com/gofiber/contrib/tree/main/v3), and fails when one is missing here. Run it yourself with `bash .github/scripts/check-middleware-coverage.sh`. Third-party entries stay a pull request away, since nothing can discover them automatically.

## Quality standards

To be on the list, project repositories should adhere to these quality standards (`https://goreportcard.com/report/github.com/<github_user>/<github_repo>`):

- Code functions as documented and expected
- Generally useful to the wider community of Go programmers
- Actively maintained
  - Regular, recent commits
  - Or, for finished projects, issues and pull requests are responded to
- Stable or progressing toward stable
- Thoroughly documented (README, pkg.go.dev doc comments, etc.) in English, so everyone is able to understand the project's intention and how it works

## Congrats, your project got accepted - what now?

You are an awesome project now! Feel encouraged to tell others about it by adding one of these badges:  
[![Mentioned in Awesome Fiber](https://awesome.re/mentioned-badge.svg)](https://github.com/gofiber/awesome-fiber)  
[![Mentioned in Awesome Fiber](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/gofiber/awesome-fiber)

```md
[![Mentioned in Awesome Fiber](https://awesome.re/mentioned-badge.svg)](https://github.com/gofiber/awesome-fiber)  
[![Mentioned in Awesome Fiber](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/gofiber/awesome-fiber)
```

## Reporting issues

Please open an issue if you would like to discuss anything that could be improved or have suggestions for making the list a more valuable resource. We realize sometimes packages fall into abandonment or have breaking builds for extended periods of time, so if you see that, feel free to change its listing or let us know. We also realize that sometimes projects are just going through transitions or are more experimental in nature. These can still be cool, but we can indicate them as transitory or experimental.

Thanks everyone!
