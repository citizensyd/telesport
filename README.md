<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>TELESPORT</h1>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/esbuild-FFCF00.svg?style=flat-square&logo=esbuild&logoColor=black" alt="esbuild" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat-square&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style=flat-square&logo=PostCSS&logoColor=white" alt="PostCSS" />
<img src="https://img.shields.io/badge/Autoprefixer-DD3735.svg?style=flat-square&logo=Autoprefixer&logoColor=white" alt="Autoprefixer" />
<img src="https://img.shields.io/badge/Sass-CC6699.svg?style=flat-square&logo=Sass&logoColor=white" alt="Sass" />
<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=flat-square&logo=YAML&logoColor=white" alt="YAML" />
<img src="https://img.shields.io/badge/Webpack-8DD6F9.svg?style=flat-square&logo=Webpack&logoColor=black" alt="Webpack" />
<img src="https://img.shields.io/badge/Jasmine-8A4182.svg?style=flat-square&logo=Jasmine&logoColor=white" alt="Jasmine" />
<img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style=flat-square&logo=ESLint&logoColor=white" alt="ESLint" />

<img src="https://img.shields.io/badge/SemVer-3F4551.svg?style=flat-square&logo=SemVer&logoColor=white" alt="SemVer" />
<img src="https://img.shields.io/badge/Lodash-3492FF.svg?style=flat-square&logo=Lodash&logoColor=white" alt="Lodash" />
<img src="https://img.shields.io/badge/Stylus-333333.svg?style=flat-square&logo=Stylus&logoColor=white" alt="Stylus" />
<img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=flat-square&logo=TypeScript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Ajv-23C8D2.svg?style=flat-square&logo=Ajv&logoColor=white" alt="Ajv" />
<img src="https://img.shields.io/badge/Buffer-231F20.svg?style=flat-square&logo=Buffer&logoColor=white" alt="Buffer" />
<img src="https://img.shields.io/badge/Less-1D365D.svg?style=flat-square&logo=Less&logoColor=white" alt="Less" />
<img src="https://img.shields.io/badge/Socket.io-010101.svg?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.io" />
<img src="https://img.shields.io/badge/Express-000000.svg?style=flat-square&logo=Express&logoColor=white" alt="Express" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat-square&logo=JSON&logoColor=white" alt="JSON" />
</p>
<img src="https://img.shields.io/github/license/citizensyd/telesport?style=flat-square&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/citizensyd/telesport?style=flat-square&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/citizensyd/telesport?style=flat-square&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/citizensyd/telesport?style=flat-square&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [🚀 Getting Started](#-getting-started)
  - [🔧 Installation](#-installation)
  - [🤖 Running telesport](#-running-telesport)
- [🛣 Project Roadmap](#-project-roadmap)
- [🤝 Contributing](#-contributing)
    - [*Contributing Guidelines*](#contributing-guidelines)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

In this project, you are tasked with developing the front-end of a new web application for TéléSport to enhance their Olympic Games coverage. Utilizing Angular, the application will feature an interactive dashboard displaying historical Olympic data, such as medal counts. You will be following Angular best practices, including efficient HTTP requests, RxJS observables, and strong typing. Resources provided include starter code, UX designs, and project specifications. Your manager, Jeannette, has limited time for direct meetings but provides a detailed video explanation. The final deliverable is a public GitHub repository containing all code and documentation, culminating in an oral presentation where you'll demonstrate the application, discuss its architecture, and justify your technical choices.

---

## 📦 Features

This project features the development of an interactive web application for TéléSport, focused on the Olympic Games. It involves creating a dynamic dashboard using Angular, showcasing historical Olympic data, including medal counts by country. Key features include adherence to Angular best practices, utilization of RxJS observables for data handling, and responsive design for compatibility across devices. The project is supported by comprehensive resources such as starter code, UX designs, and detailed specifications. The deliverable includes a fully documented and publicly accessible GitHub repository, culminating in an evaluative presentation to demonstrate the application's functionality and discuss its technical architecture.

---


## 📂 Repository Structure

```sh
└── telesport/
    ├── .browserslistrc
    ├── angular.json
    ├── karma.conf.js
    ├── package-lock.json
    ├── package.json
    ├── src/
    │   ├── app/
    │   │   ├── app-routing.module.ts
    │   │   ├── app.component.html
    │   │   ├── app.component.scss
    │   │   ├── app.component.spec.ts
    │   │   ├── app.component.ts
    │   │   ├── app.module.ts
    │   │   ├── charts/
    │   │   ├── components/
    │   │   ├── core/
    │   │   ├── pages/
    │   │   └── statistic-card/
    │   ├── environments/
    │   │   ├── environment.prod.ts
    │   │   └── environment.ts
    │   ├── index.html
    │   ├── main.ts
    │   ├── polyfills.ts
    │   ├── styles/
    │   │   └── _variables.scss
    │   ├── styles.scss
    │   └── test.ts
    ├── tsconfig.app.json
    ├── tsconfig.json
    ├── tsconfig.spec.json
    └── yarn.lock

```

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

    ℹ️ Node.js: A compatible version with Angular 14. Typically, Node.js version 14 or later is recommended.

    ℹ️ Angular CLI: Version 14.1.3 or later. This is essential for developing Angular applications.

    ℹ️ @angular/animations, @angular/common, @angular/compiler, @angular/core, @angular/forms, @angular/platform-browser, @angular/platform-browser-dynamic, @angular/router: All version 14.1.0. These are core Angular modules necessary for building Angular applications.

    ℹ️ @swimlane/ngx-charts: Version 20.5.0. Used for creating charts and visualizations.

    ℹ️ TypeScript definitions for D3: Including @types/d3-scale version 4.0.8, @types/d3-selection version 3.0.10, and @types/d3-shape version 3.1.6 for D3 integration.

    ℹ️ RxJS: Version 7.5.0. A reactive programming library for managing asynchronous data.

    ℹ️ Tslib: Version 2.3.0. The runtime library for TypeScript.

    ℹ️ Zone.js: Version 0.11.4. A library for asynchronous operations management in Angular.

    ℹ️ Additional Installation Packages: Such as install version 0.13.0.

For the Development Environment:

    ℹ️ @angular-devkit/build-angular: Version 14.1.3. This package is used for building Angular apps.

    ℹ️ Testing Tools: Including Jasmine (@types/jasmine version 4.0.0, jasmine-core version 4.2.0) and Karma (karma version 6.4.0, karma-chrome-launcher version 3.1.0, karma-coverage version 2.2.0, karma-jasmine version 5.1.0, karma-jasmine-html-reporter version 2.0.0) for unit testing.

    ℹ️ TypeScript: Version 4.7.2 for Angular application development.

### 🔧 Installation

1. Clone the telesport repository:
```sh
git clone https://github.com/citizensyd/telesport
```

2. Change to the project directory:
```sh
cd telesport
```

3. Install the dependencies:
```sh
npm install
```

### 🤖 Running telesport

```sh
npm start
```

---


## 🛣 Project Roadmap

> - [X] `ℹ️  Step 1: Starter Code Setup

    Ensure installations of Git, Node, and npm.
    Clone the project from GitHub to your local machine.`
> - [x] `ℹ️  Step 2: Understanding and Defining Data

    Retrieve data via HTTP requests.
    Define TypeScript types/interfaces for the data.`
> - [x] `ℹ️ Step 3: Library Selection and Setup

    Choose a suitable library for chart creation.
    Implement the first chart and understand Angular's navigation.`
> - [x] `ℹ️ Step 4: Dashboard Creation

    Develop the homepage with the required interactive chart.
    Ensure responsiveness and adherence to provided designs.`
> - [x] `ℹ️ Step 5: Detail Page Creation

    Build the detailed view page with navigation from the homepage.
    Manage state changes and HTTP requests efficiently.`
> - [x] `ℹ️ Step 6: Code Cleanup and Documentation

    Finalize all features as per the project specifications.
    Test the application thoroughly and handle any potential errors.
    Document the code and usage instructions in a README file.
    Make the project publicly available on GitHub.`


---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/citizensyd/telesport/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/citizensyd/telesport/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/citizensyd/telesport/issues)**: Submit bugs found or log feature requests for CITIZENSYD.

#### *Contributing Guidelines*

<details closed>
<summary>Click to expand</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone <your-forked-repo-url>
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear and concise message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---

## 📄 License


This project is protected under the MIT License. For more details, refer to the LICENSE file.

---

## 👏 Acknowledgments

- Special thanks to my mentor, Hichem, for his invaluable guidance and support. I'm also grateful to OpenClassrooms for providing an excellent learning platform that has significantly contributed to my development journey.

[**Return**](#Top)

---

