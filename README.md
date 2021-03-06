# NEAR Certified Developer (NCD) - Day 0

Curated list of things you should have and know before you attend [NCD I](https://hackmd.io/@nearly-learning/ncd-1-1d) and [NCD II](https://hackmd.io/@nearly-learning/ncd-1-1d) to succeed

Don't worry if you don't have and know all reccomended things, you are still welcomed to join and find out what it takes to be NEAR Certified Developer.

However, don't forget that to get the NCD I and II certificates that you have to succesfully present demo.

## What you SHOULD have

Software that you **should** have installed in your computer in order to be able to work on content discussed in NCD I and II.

- [GIT](https://git-scm.com/downloads) - to get sample projects from GitHub to your computer and to later share your project with others
- [Node.js](https://nodejs.org/en/download/) - to install 3rd party libraries to sample project you downloaded from GitHub
- [Yarn](https://yarnpkg.com/getting-started/install) - (reccomended) - basically, this is more user friendly version of npm and our npm scripts are using yarn
- [near-cli](https://github.com/near/near-cli#setup) - to deploy your first smart contract
- Code editor like [VS Code](https://code.visualstudio.com/), [Sublime Text](https://www.sublimetext.com/), [Atom](https://atom.io/) or any other favorite (you will have hard time coding if you don't have the code editor)
- [NEAR testnet Wallet](https://wallet.testnet.near.org/) - (reccomended) - created and [logged in near-cli](https://docs.near.org/docs/tools/near-cli)

## What you SHOULD know

Technologies you should know before attending NCD I and NCD II, without this you will have hard time understanding what we are teaching.

- [HTML basics](https://www.w3schools.com/html/default.asp) - to create UI
- [JavaScript basics](https://www.w3schools.com/js/default.asp) - to be able to call NEAR smart contract from front-end (UI)
- [TypeScript basics](https://www.freecodecamp.org/news/learn-typescript-basics/) or [AssemblyScript basics](https://www.assemblyscript.org/basics.html#strictness) or [Rust basics](https://doc.rust-lang.org/stable/rust-by-example/) - to create your NEAR smart contract
- [Shell (Bash) basics](https://linuxconfig.org/bash-scripting-tutorial-for-beginners) - (optional) - to help you with `near-cli` and other command line scripts

## NCD I - Day 0

Get familiar with NEAR smart contract starter project

1. Get [starter project](https://github.com/Learn-NEAR/starter--near-sdk-as) to your PC -> `git clone <url>`
2. Check `./scripts` and see how smart contract works
3. Change something in `./scr/simple/assembly/index.ts` or in `./scr/singleton/assembly/index.ts` and run scripts again to see how behavior changed

## NCD II - Day 0

Get familiar with NEAR smart contract front-end starter project

1. Get [starter project](https://github.com/Learn-NEAR/starter--near-api-js) to your PC -> `git clone <url>`
2. Open `./index.html` in your browser
3. Test the app and try to log in
4. Now change contradId in files to one you generated in NCD I and see the changes

## Bonus tasks

1. Add new methods to smart contract from NCD I starter project and try to call them via UI of NCD II starter project
2. Check [other sample projects](https://github.com/orgs/Learn-NEAR/repositories) for inspiration

> Congratulations! If you got there and finished all tasks, you will have no issues getting your NCD I and NCD II certifications!
