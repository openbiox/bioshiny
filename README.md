<p align="center">
  <a href="https://github/openbiox/bioshiny">
    <img
      alt="bioshiny"
      src="https://raw.githubusercontent.com/openbiox/bioshiny/master/doc/images/bioshiny-logo.svg?sanitize=true"
      width="200"
    />
  </a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/bioshiny"><img src="https://img.shields.io/badge/lifecycle-experimental-orange.svg" alt="Life cycle: experimental">
  <a href="https://circleci.com/gh/openbiox/bioshiny/tree/master"><img src="https://img.shields.io/circleci/project/github/openbiox/bioshiny/master.svg" alt="Build Status"></a>
  <a href="https://npmcharts.com/compare/bioshiny?minimal=true"><img src="https://img.shields.io/npm/dm/bioshiny.svg" alt="Downloads"></a>
  <a href="https://www.npmjs.com/package/bioshiny"><img src="https://img.shields.io/npm/v/bioshiny.svg" alt="Version"></a>
  <a href="https://www.npmjs.com/package/bioshiny"><img src="https://img.shields.io/npm/l/bioshiny.svg" alt="License"></a>
</p>

[bioshiny](https://github.com/openbiox/bioshiny) is a project to develop the R Shiny applications for bioinformatics research.

# bioshiny

- One-click to create bioshiny Shiny application and plugins
- Create and share more plugins.
- Using [npm](https://www.npmjs.com/) and GitHub to share the Shiny applications and plugins (CRAN team limited file size)

![](https://raw.githubusercontent.com/Miachol/ftp/master/files/images/bioinstaller/overview2.jpg)

![](https://raw.githubusercontent.com/Miachol/ftp/master/files/images/bioinstaller/overview1.jpg)

![](https://raw.githubusercontent.com/Miachol/ftp/master/files/images/bioinstaller/overview3.jpg)
o
![](https://raw.githubusercontent.com/Miachol/ftp/master/files/images/bioinstaller/overview4.jpg)

![](https://raw.githubusercontent.com/Miachol/ftp/master/files/images/bioinstaller/overview4.jpg)

## Installation

```bash
git clone https::/github.com/openbiox/bioshiny
cd bioshiny
yarn global add `pwd`
bioshiny_deps_r
bioshiny_deps_js
```

## Usage

```bash
Rscript -e "bioshiny::set_shiny_workers(1)"
bioshiny_start
```

## How to contribute?

Please fork the [GitHub bioshiny
repository](https://github.com/openbiox/bioshiny), modify it, and
submit a pull request to us. 

## Maintainer

[Jianfeng Li](https://github.com/Miachol)

## License

MIT
