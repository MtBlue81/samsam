# Changes

## 6.1.1

- [`0a89fbd`](https://github.com/sinonjs/samsam/commit/0a89fbd6e186a7343a6369e924457e2fa14df710)
  Bump cached-path-relative from 1.0.2 to 1.1.0 (#227) (dependabot[bot])
    > Co-authored-by: dependabot[bot] <49699333+dependabot[bot]@users.noreply.github.com>
- [`88a3fca`](https://github.com/sinonjs/samsam/commit/88a3fca262b3a4bc29b53635bb8ec5c2a3925a5b)
  Install missing dependency mkdocs and update lock file version (Carl-Erik Kopseng)

_Released on 2022-01-28._

## 6.1.0

- [`6955f94`](https://github.com/sinonjs/samsam/commit/6955f94b414049f21971c19a0f97c1b5f922126f)
  fix (#226) (Stuart Dotson)
- [`f1a1f30`](https://github.com/sinonjs/samsam/commit/f1a1f306018166ad76ab1a1a71d400fc9373f7d0)
  add support for iterables (#225) (Stuart Dotson)
- [`2bc9f80`](https://github.com/sinonjs/samsam/commit/2bc9f80ab886653f4995c60b09af93e0216a9724)
  Bump path-parse from 1.0.6 to 1.0.7 (dependabot[bot])
- [`64dfb5d`](https://github.com/sinonjs/samsam/commit/64dfb5d1f477033b5e5a3b7e037e921048ddef5e)
  Bump ws from 6.2.1 to 6.2.2 (dependabot[bot])
- [`d41050b`](https://github.com/sinonjs/samsam/commit/d41050be94d214b15a2cecb18cc0c36d6141fd82)
  Bump browserslist from 4.16.3 to 4.16.6 (dependabot[bot])

_Released on 2022-01-27._

## 6.0.2

- [`144204d`](https://github.com/sinonjs/samsam/commit/144204d505526d5c382cb2f3dc2c2dd1378fe12d)
  Fix deep equal comparison between promises (#217) (David G. Miguel)

_Released on 2021-05-24._

## 6.0.1

- [`decfafe`](https://github.com/sinonjs/samsam/commit/decfafe72d8b2d159cfc49440a8f4af6d3e9c574)
  Bump y18n from 4.0.0 to 4.0.1 (dependabot[bot])
    >
    > Bumps [y18n](https://github.com/yargs/y18n) from 4.0.0 to 4.0.1.
    > - [Release notes](https://github.com/yargs/y18n/releases)
    > - [Changelog](https://github.com/yargs/y18n/blob/master/CHANGELOG.md)
    > - [Commits](https://github.com/yargs/y18n/commits)
    >
    > Signed-off-by: dependabot[bot] <support@github.com>

_Released on 2021-04-08._

## 6.0.0

- [`95d1dce`](https://github.com/sinonjs/samsam/commit/95d1dce07f47b7bbb84111c42f44ecd9466dc2c8)
  Use @sinonjs/eslint-config (Morgan Roderick)
    >
    > This drops support for legacy runtimes like IE11, legacy Edge, Safari 9 and the like

_Released on 2021-03-30._

## 5.3.1

- [`04e0faa`](https://github.com/sinonjs/samsam/commit/04e0faa88d8a08325c6d70febed9dad4e7eeabfe)
  Distribute package as source (Morgan Roderick)
    >
    > This library is not meant for writing end user applications or even for
    > being used directly when writing tests. It is not meant to be loaded
    > directly by browsers.
    >
    > Consumers of this package are assumed to use their own bundlers, should
    > they need to bundle code for use in browsers or workers.
    >
    > Therefore, it is safe to distribute the package as source files and not
    > bundle them up.
    >
    > This allows us to remove the bundler and its transitive dependencies,
    > which reduces the maintenance burden of managing the library.
    >

_Released on 2021-01-13._

## 5.3.0

- [`fd8aabd`](https://github.com/sinonjs/samsam/commit/fd8aabd3768c199abc717dc6d793ef136419be72)
  Generate .d.ts from JSDoc (Morgan Roderick)
    >
    > See https://humanwhocodes.com/snippets/2020/10/create-typescript-declarations-from-javascript-jsdoc/
    >

_Released on 2020-11-16._

## 5.2.0

- [`f27b87c`](https://github.com/sinonjs/samsam/commit/f27b87cbd493a09e4a3181cf36f503facbbb23fb)
  Add match.json (Maximilian Antoni)

_Released by [Maximilian Antoni](https://github.com/mantoni) on 2020-10-06._

## 5.1.0

- [`820c296`](https://github.com/sinonjs/samsam/commit/820c2961f70208367e1c072ae9a581eefd0d8d18)
  Evaluate symbol keys for object matchers (#206) (Joel Bradshaw)
    >
    > * Make match() work for objects with symbol keys

_Released on 2020-08-11._

## 5.0.3

- [`9d2add0`](https://github.com/sinonjs/samsam/commit/9d2add01eba85eb17ddb91ac22404fb6c23e8d39)
  Remove unused @sinonjs/formatio (Morgan Roderick)
    >
    > As can be seen with searching the codebase, @sinonjs/formatio is never
    > imported, and is thus not a direct dependency of @sinonjs/samsam.
    >

_Released on 2020-02-28._

## 5.0.2

- [`f9e845a`](https://github.com/sinonjs/samsam/commit/f9e845a52ba50916df91335d2003a81a808a4ade)
  Bump formatio to latest major (Morgan Roderick)
    >
    > This will remove some duplication in Sinon, see https://github.com/sinonjs/sinon/issues/2224
    >

_Released on 2020-02-20._

## 5.0.1

- [`fe5d035`](https://github.com/sinonjs/samsam/commit/fe5d03532ea6cdbec857c49d18392d668cca8ef2)
  Bump jsdom from 15.2.1 to 16.2.0 (dependabot-preview[bot])
    >
    > Bumps [jsdom](https://github.com/jsdom/jsdom) from 15.2.1 to 16.2.0.
    > - [Release notes](https://github.com/jsdom/jsdom/releases)
    > - [Changelog](https://github.com/jsdom/jsdom/blob/master/Changelog.md)
    > - [Commits](https://github.com/jsdom/jsdom/compare/15.2.1...16.2.0)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`910af18`](https://github.com/sinonjs/samsam/commit/910af18be1bd57c6237399ca04cbef91d994a38a)
  Remove maintenance junk from CHANGES.md (Morgan Roderick)

_Released on 2020-02-18._

## 5.0.0

- [`f288430`](https://github.com/sinonjs/samsam/commit/f2884309c9bf68b02ecfda3bd1df8d7a7a31686b)
  Drop support for Node 8 (Morgan Roderick)
    >
    > As can be seen at https://github.com/nodejs/Release, Node 8 reached
    > "end" of life on 2019-12-31, and is no longer actively supported.
    >
    > We will stop testing in Node 8 and start testing in Node 13, which will
    > become the next LTS release from April 2020.
    >

_Released on 2020-02-18._

## 4.2.2

- [`c600d6c`](https://github.com/sinonjs/samsam/commit/c600d6cb6c1bec8d65bc718bd9268311204597bc)
  Fix issue with nested array matching (Jay Merrifield)
- [`8b37566`](https://github.com/sinonjs/samsam/commit/8b37566ea73bee512fbc4203c07678288f906bda)
  Bump eslint from 6.7.2 to 6.8.0 (dependabot-preview[bot])
    >
    > Bumps [eslint](https://github.com/eslint/eslint) from 6.7.2 to 6.8.0.
    > - [Release notes](https://github.com/eslint/eslint/releases)
    > - [Changelog](https://github.com/eslint/eslint/blob/master/CHANGELOG.md)
    > - [Commits](https://github.com/eslint/eslint/compare/v6.7.2...v6.8.0)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`b7c5db9`](https://github.com/sinonjs/samsam/commit/b7c5db9e7847204188c112843bb193248d0b5156)
  Bump eslint-plugin-prettier from 3.1.1 to 3.1.2 (dependabot-preview[bot])
    >
    > Bumps [eslint-plugin-prettier](https://github.com/prettier/eslint-plugin-prettier) from 3.1.1 to 3.1.2.
    > - [Release notes](https://github.com/prettier/eslint-plugin-prettier/releases)
    > - [Changelog](https://github.com/prettier/eslint-plugin-prettier/blob/master/CHANGELOG.md)
    > - [Commits](https://github.com/prettier/eslint-plugin-prettier/compare/v3.1.1...v3.1.2)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`8965384`](https://github.com/sinonjs/samsam/commit/8965384818697b7b36537619922b3c378bfd0b42)
  Bump eslint-plugin-mocha from 6.1.1 to 6.2.2 (dependabot-preview[bot])
    >
    > Bumps [eslint-plugin-mocha](https://github.com/lo1tuma/eslint-plugin-mocha) from 6.1.1 to 6.2.2.
    > - [Release notes](https://github.com/lo1tuma/eslint-plugin-mocha/releases)
    > - [Changelog](https://github.com/lo1tuma/eslint-plugin-mocha/blob/master/CHANGELOG.md)
    > - [Commits](https://github.com/lo1tuma/eslint-plugin-mocha/compare/6.1.1...6.2.2)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`8661610`](https://github.com/sinonjs/samsam/commit/866161044e212b4df56a207e55ab3e449346abf5)
  Bump eslint-config-prettier from 6.7.0 to 6.9.0 (dependabot-preview[bot])
    >
    > Bumps [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier) from 6.7.0 to 6.9.0.
    > - [Release notes](https://github.com/prettier/eslint-config-prettier/releases)
    > - [Changelog](https://github.com/prettier/eslint-config-prettier/blob/master/CHANGELOG.md)
    > - [Commits](https://github.com/prettier/eslint-config-prettier/commits/v6.9.0)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`7d91124`](https://github.com/sinonjs/samsam/commit/7d91124a9fa95c462c1e714d86405d6cb99e3363)
  Bump rollup from 1.23.0 to 1.27.14 (dependabot-preview[bot])
    >
    > Bumps [rollup](https://github.com/rollup/rollup) from 1.23.0 to 1.27.14.
    > - [Release notes](https://github.com/rollup/rollup/releases)
    > - [Changelog](https://github.com/rollup/rollup/blob/master/CHANGELOG.md)
    > - [Commits](https://github.com/rollup/rollup/compare/v1.23.0...v1.27.14)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`31c616a`](https://github.com/sinonjs/samsam/commit/31c616ab278e05071138e18d6e5aea8f2c250c2a)
  Bump nyc from 14.1.1 to 15.0.0 (dependabot-preview[bot])
    >
    > Bumps [nyc](https://github.com/istanbuljs/nyc) from 14.1.1 to 15.0.0.
    > - [Release notes](https://github.com/istanbuljs/nyc/releases)
    > - [Changelog](https://github.com/istanbuljs/nyc/blob/master/CHANGELOG.md)
    > - [Commits](https://github.com/istanbuljs/nyc/compare/v14.1.1...v15.0.0)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`e82dbcf`](https://github.com/sinonjs/samsam/commit/e82dbcf9af6a052b1d466e476a7315e047324256)
  Bump @sinonjs/referee from 3.2.0 to 4.0.0 (dependabot-preview[bot])
    >
    > Bumps [@sinonjs/referee](https://github.com/sinonjs/referee) from 3.2.0 to 4.0.0.
    > - [Release notes](https://github.com/sinonjs/referee/releases)
    > - [Changelog](https://github.com/sinonjs/referee/blob/master/CHANGES.md)
    > - [Commits](https://github.com/sinonjs/referee/compare/v3.2.0...v4.0.0)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`b089354`](https://github.com/sinonjs/samsam/commit/b089354118a6f64139ca64906d8b8a9f282bc376)
  Bump eslint-plugin-jsdoc from 18.4.3 to 19.2.0 (dependabot-preview[bot])
    >
    > Bumps [eslint-plugin-jsdoc](https://github.com/gajus/eslint-plugin-jsdoc) from 18.4.3 to 19.2.0.
    > - [Release notes](https://github.com/gajus/eslint-plugin-jsdoc/releases)
    > - [Commits](https://github.com/gajus/eslint-plugin-jsdoc/compare/v18.4.3...v19.2.0)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`bba8c44`](https://github.com/sinonjs/samsam/commit/bba8c441914cd3b07b505b4d917a042d16412c9e)
  Bump @sinonjs/commons from 1.6.0 to 1.7.0 (dependabot-preview[bot])
    >
    > Bumps [@sinonjs/commons](https://github.com/sinonjs/commons) from 1.6.0 to 1.7.0.
    > - [Release notes](https://github.com/sinonjs/commons/releases)
    > - [Commits](https://github.com/sinonjs/commons/compare/v1.6.0...v1.7.0)
    >
    > Signed-off-by: dependabot-preview[bot] <support@dependabot.com>
- [`5915960`](https://github.com/sinonjs/samsam/commit/5915960fab257e27564c544da45b419c360bc8fb)
  Publish using public access (Morgan Roderick)
- [`28ffc83`](https://github.com/sinonjs/samsam/commit/28ffc83556274b025d1fc62b52d2ff8ea25743a4)
  4.2.1 (Morgan Roderick)

_Released by [Maximilian Antoni](https://github.com/mantoni) on 2020-01-09._

## 4.2.1

- [`8987966`](https://github.com/sinonjs/samsam/commit/898796645000b88f1a4045213355bed29085f46c)
  re-introduce bound deepEqual (#160) (James Garbutt)

_Released on 2019-12-30._
