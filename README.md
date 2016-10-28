# typescript-issue-11882
Reproduction for [Microsoft/Typescript#11882](https://github.com/Microsoft/TypeScript/issues/11882)

## Steps to reproduce

* Open `App.sln`
* Open `Client\bar.ts` or `phantomcss\foo.ts`
* Notice there is no language service

## Possible fixes

* Remove the `types` config option from `phantomcss\tsconfig.json`
* run `npm install` in `phantomcss`
