# OpenCode Screen-Specific Migration Prompt

## TASK: Migrate a Specific Screen from the Legacy Application

I want to migrate the following screen:

**Screen / Module Name:** \[ENTER SCREEN NAME\]

**Business Description (optional):** \[DESCRIBE WHAT THE SCREEN DOES\]

You already have access to the source application and imported
destination framework.

You are responsible for discovering all relevant files and determining
the correct destination implementation location independently.

## PHASE 1 --- SOURCE CODE DISCOVERY

Search the entire accessible source repository.

Identify:

1.  The primary implementation of the requested screen.
2.  All related HTML, JavaScript, jQuery, CSS and other files.
3.  Nested folders and subdirectories.
4.  Imported scripts and shared dependencies.
5.  Functions invoked by the screen.
6.  Event handlers and user interactions.
7.  API calls and backend dependencies.
8.  Form validations and business rules.
9.  Navigation entry points.
10. Other screens connected to this screen.

Do not assume the screen's filename matches its displayed name.

Follow code references and dependencies to understand the complete
implementation.

Do not modify any source files.

## PHASE 2 --- DESTINATION CODE DISCOVERY

Inspect the imported destination framework.

Identify:

1.  The correct architectural location for this screen.
2.  Existing screens with similar functionality.
3.  Reusable components.
4.  Existing layouts and page containers.
5.  Routing and navigation conventions.
6.  Services and API integration patterns.
7.  Styling and design conventions.
8.  Existing shared utilities.

Determine the correct destination file structure.

Do not create a structure based on the legacy application.

## PHASE 3 --- FUNCTIONALITY MAPPING

Prepare a detailed mapping:

  -----------------------------------------------------------------------
  Source functionality    Existing implementation Destination
                                                  implementation
  ----------------------- ----------------------- -----------------------
  Screen layout           Legacy implementation   Destination layout

  Form fields             Legacy implementation   Destination form
                                                  components

  Validations             Existing rules          Destination validation
                                                  approach

  API integration         Existing API calls      Destination service
                                                  pattern

  Navigation              Legacy navigation       Destination routing

  User interactions       Legacy event handlers   Destination framework
                                                  mechanisms
  -----------------------------------------------------------------------

Include all functionality discovered, not just the examples above.

## PHASE 4 --- DESIGN MAPPING

The destination framework's existing UI design is mandatory.

Inspect similar destination screens and reuse their design patterns.

Map the source screen's functionality into the destination's:

-   Layout.
-   Typography.
-   Colours.
-   Spacing.
-   Buttons.
-   Form controls.
-   Tables.
-   Dialogs.
-   Navigation.
-   Responsive behaviour.

Do not copy the old screen's styling.

Do not independently redesign the destination application.

## PHASE 5 --- NAVIGATION ANALYSIS

Identify:

-   How users reach this screen.
-   Which existing screens navigate to it.
-   Which screens it navigates to.
-   Whether route parameters are required.
-   Whether query parameters are required.
-   Whether menu configuration must be updated.
-   Whether authentication or authorization applies.

Determine the exact destination navigation changes required.

## PHASE 6 --- MIGRATION PLAN

Before editing any files, present:

1.  Discovered source files and their paths.
2.  Related dependencies and subdirectories.
3.  Complete functionality inventory.
4.  Destination files and components identified.
5.  Proposed destination file structure.
6.  Required routing and navigation changes.
7.  Component reuse strategy.
8.  Design implementation strategy.
9.  API integration strategy.
10. Potential risks and unresolved questions.

**WAIT FOR MY APPROVAL.**

Do not create or modify files before approval.

## PHASE 7 --- IMPLEMENTATION

After approval:

-   Implement the screen using the destination framework's existing
    technology stack.
-   Follow its existing architecture.
-   Reuse shared components.
-   Maintain its existing design language.
-   Preserve all source business functionality.
-   Implement navigation correctly.
-   Avoid unrelated modifications.

## PHASE 8 --- VALIDATION

After implementation:

-   Verify all discovered source functionality.
-   Verify form validations.
-   Verify API integrations.
-   Verify user interactions.
-   Verify navigation.
-   Verify visual consistency with destination screens.
-   Run relevant build and validation commands.
-   Check for unintended impacts on other screens.

Do not claim successful testing without actually executing it.

## PHASE 9 --- FINAL MIGRATION REPORT

Report:

-   Source files discovered.
-   Destination files created.
-   Destination files modified.
-   Functionality migrated.
-   Shared components reused.
-   Navigation changes.
-   Build results.
-   Validation results.
-   Remaining issues.

## IMPORTANT

Do not guess file locations.

Do not migrate only the primary HTML file.

Discover the complete source implementation and dependencies before
proposing the migration.
