# Angular10AppSetup

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

















UI Terminology & Taxonomy Alignment:
Successfully rolled out the structural rename from Products → Definition Packages across the sidebar navigation, page headers, Viewer, Availability, Creation, Promotion, and Activity Log.
Enhanced Search & Discovery:
Decoupled package types and product/LOB filters into dedicated dropdowns in the Definition Package Viewer, eliminating ambiguity and making Underwriting Questions straightforward to locate.
Authoring Flow & Visual Editor Improvements:
Repositioned "Add Attribute" action buttons to the top of definition attribute panels, removing extensive scrolling on large definitions such as CGL
Fixed Visual Editor in-progress definition precedence resolution, allowing users to reference in-progress definitions/local hrefs without being forced to edit raw JSON .
Restored sidebar jump-link navigation in the Visual Editor during definition creation from scratch.
Lifecycle Parity for Underwriting Questions (UWQ):
Enabled demotion of UWQ definitions from Beta back to Alpha, giving authors full rollback and iteration flexibility matching Coverage Definitions.
Bug Bash Fixes & UI Refinements:
Resolved menu z-index conflicts preventing dropdown overlaps
Split composite links in the "Used By" section into discrete target links for components and containers
De-cluttered the Activity Log by eliminating redundant multi-selection context displays.
Operations & Engineering Productivity:
Configured app performance Datadog monitors integrated with Slack alerting for proactive issue detection
Authored comprehensive onboarding documentation for Test Engineers covering schemas, promotions, and tooling





