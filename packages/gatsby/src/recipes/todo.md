- [x] Make root configurable/dynamic
- [x] Make recipe configurable (theme-ui/eslint/jest)
- [x] Exit upon completion

- [x] Move into gatsby repo
- [x] Run as a command
- [x] Boot up server as a process
- [x] Then run the CLI
- [x] Clean up server after
- [ ] show plan to create or that nothing is necessary & then show in `<static>` what was done

## alpha

- [x] Handle `dev` in NPMPackage
- [x] add Joi for validating resource objects
- [x] handle template strings in JSX parser
- [x] Step by step design
- [x] Use `fs-extra`
- [x] Handle object style plugins
- [x] Improve gatsby-config test
- [x] convert to xstate
- [x] integration test for each resource (read, create, update, delete)
- [x] validate Resource component props.
- [x] reasonably test resources
- [x] add Joi for validating resource objects
- [x] handle error states
- [x] handle template strings in JSX parser
- [x] Make it support relative paths for custom recipes (./src/recipes/foo.mdx)
- [x] Move parsing to the server
- [x] run recipe from url
- [x] Move parsing to the server
- [x] imports from a url
- [x] Document the supported components and trivial guide on recipe authoring
- [x] have File only pull from remote files for now until multiline strings work in MDX
- [ ] Make port selection dynamic
- [ ] Add large warning to recipes output that this is an experimental feature & might change at any moment + link to docs / umbrella issue for bug reports & discussions
- [ ] use yarn/npm based on the user config
- [ ] test modifying gatsby-config.js from default starter
- [ ] integration test for each resource (read, create, update, delete)
- [ ] spike on bundling recipes into one file
- [ ] update shadow file resource
- [ ] write tests for remote files src in File
- [ ] Gatsby recipes list (design and implementation)
- [ ] print pretty error when there's parsing errors of mdx files
- [ ] Move gatsby/src/recipes to its own package `gatsby-recipes` & pull them from unpkg w/ make-fetch-happen/file-system-cache
- [ ] handle people pressing Y & quit if they press "n" (for now)
- [ ] handle error states
- [ ] validate that the first step of recipes don't have any resources. They should just be for the title/description
- [ ] diff all resource changes — add test for all resources that they return something for this & remove current/new state
- [ ] move code to its own package `gatsby-recipes`
- [ ] handle not finding a recipe
- [ ] write blog post

## Near-ish future

- [ ] Make a proper "Config" provider to add recipes dir, store data, etc.
- [ ] init.js for providers to setup clients
- [ ] validate resource config
- [ ] Theme UI preset selection (runs dependent install and file write)
- [ ] Select input supported recipes
- [ ] Refactor resource state to use Redux & record runs in local db
- [ ] move creating the validate function to core and out of resources — they just declare their schema
- [ ] gatsby-config.js hardening — make it work if there's no plugins set like in hello-world starter
- [ ] get latest version of npm packages so know if can skip running.
- [ ] Make `dependencyType` in NPMPackage an enum (joi2gql doesn't handle this right now from Joi enums)
- [ ] Show in plan if an update will be applied vs. create.
- [ ] Implement config object for GatsbyPlugin
- [ ] Handle JS in config objects? { **\_javascript: "`\${**dirname}/foo/bar`" }