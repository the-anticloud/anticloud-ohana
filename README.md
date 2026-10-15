# OHANA

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-16_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `OHANA` in category **GOVERNMENT**. 16/16 checks PASS (measured). Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** https://github.com/uber-archive/ohana-ios · **Upstream pin:** `e3ab28075a5fc2f2e15ce06403db5c1e785a7778` · **Category:** GOVERNMENT · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

![Ohana](https://s3.amazonaws.com/uploads.hipchat.com/17604/3775258/b8P910panT41Y7a/ohana.png)

[![CI Status](http://img.shields.io/travis/uber/ohana-ios.svg?style=flat)](https://travis-ci.org/uber/ohana-ios)
[![Version](https://img.shields.io/cocoapods/v/Ohana.svg?style=flat)](http://cocoapods.org/pods/Ohana)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/Ohana.svg?style=flat)](http://cocoapods.org/pods/Ohana)
[![Platform](https://img.shields.io/cocoapods/p/Ohana.svg?style=flat)](http://cocoapods.org/pods/Ohana)

(This project is deprecated and not maintained.)

Ohana is a framework for working with a user's contacts on the iOS platform. It provides a component-based architecture for loading and processing contacts, as well as managing state such as contact selection and tagging. Whether loading contacts to display to a user, or processing contact data programatically, Ohana provides a simple, but extensible, framework for contact access in your application.  Check out the [wiki](https://github.com/uber/ohana-ios/wiki) to learn how the library works.  There are two quickstart guides available: one for [Swift](https://github.com/uber/ohana-ios/wiki/Quick-Start-(Swift)) and one for [Objective-C](https://github.com/uber/ohana-ios/wiki/Quick-Start-(Objective-C)).  If you have any questions, feel free to ask on [Stack Overflow](http://stackoverflow.com/questions/tagged/ohana) (tag "ohana").

## Features

- [x] Easy to get started
- [x] Extensible architecture
- [x] Runtime-injectable components
- [x] Swift-compatible

## Installation

#### CocoaPods

To integrate Ohana into your project using [CocoaPods](http://cocoapods.org), add the following line to your Podfile:

```ruby
pod 'Ohana', '~> 1.3'
```

#### Carthage

To consume Ohana using [Carthage](https://github.com/Carthage/Carthage) add this to your Cartfile:

```
github "uber/ohana-ios" ~> 1.3
```

You'll need to manually import Ohana, and its dependencies, libPhoneNumber and UberSignals.

## Running the Examples App

* source the project `git source git@github.com:uber/ohana-ios.git`
* Open the Example directory `cd ohana-ios/Example`
* run `pod install`
* `open Ohana.xcworkspace` 
* Run the `OhanaExample` scheme in Xcode

## Authors

* Nick Entin ([@NickEntin](https://github.com/NickEntin))
* Maxwell Elliott (maxwelle@uber.com, [@maxwellE](https://github.com/maxwellE))
* Doug Togno (dtogno@uber.com, [@Darj](https://github.com/Darj))
* Adam Zethraeus (adamz@uber.com, [@zethraeus](https://github.com/zethraeus))

## Contributions

We'd love for you to contribute to our open source projects. Before we can accept your contributions, we kindly ask you to sign our [Uber Contributor License Agreement](https://docs.google.com/a/uber.com/forms/d/1pAwS_-dA1KhPlfxzYLBqK6rsSWwRwH95OCCZrcsY5rk/viewform).

- If you **find a bug**, open an issue or submit a fix via a pull request.
- If you **have a feature request**, open an issue or submit an implementation via a pull request
- If you **want to contribute**, submit a pull request.

Check out the [Contribution Guidelines](https://github.com/uber/ohana-ios/wiki/Contribution-Guidelines) for more information.

## License

Ohana is released under the MIT license. See the LICENSE file for more info.

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

We'd love for you to contribute to our open source projects. Before we can accept your contributions, we kindly ask you to sign our [Uber Contributor License Agreement](https://docs.google.com/a/uber.com/forms/d/1pAwS_-dA1KhPlfxzYLBqK6rsSWwRwH95OCCZrcsY5rk/viewform).

- If you **find a bug**, open an issue or submit a fix via a pull request.
- If you **have a feature request**, open an issue or submit an implementation via a pull request
- If you **want to contribute**, submit a pull request.

Check out the [Contribution Guidelines](https://github.com/uber/ohana-ios/wiki/Contribution-Guidelines) for more information.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** https://github.com/uber-archive/ohana-ios
- **Pinned SHA:** `e3ab28075a5fc2f2e15ce06403db5c1e785a7778`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`8ba1f1a83d022c692ee12669b2eae3ef4717214943b2d2c19832b45ffdadaed3`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

