# interactive-learning
Canvas Training: Course Content Import Branching Scenario
An accessible, interactive branching scenario designed for Canvas LMS to train instructors on best practices for migrating content from prior semesters.

Overview
When instructors migrate an entire Canvas course shell using the "All Content" setting, legacy announcements and expired dates often cause confusion. This branching scenario demonstrates the consequences of uncurated course copies versus selecting specific modules and adjusting due dates in bulk.
Features & Accessibility
Canvas RCE Sanitizer-Safe: Built using pure HTML5 <details> and <summary> elements with inline CSS—no external JavaScript or <script> tags that Canvas might strip.

WCAG 2.1 AA Compliant: Text-to-background contrast ratios exceed the standard 4.5:1 minimum (#1a1a1a body text on #ffffff / #0f2d4a headers on #f0f7fc).

Multi-Modal Feedback: Uses explicit text tags ([Outcome: High Friction], [Outcome: Recommended Best Practice]) rather than relying on color alone.

Keyboard Navigable: Supports native accessibility controls (Space / Enter to expand branches, Tab to navigate).

Responsive Layout: Contained within a flexible max-width container (800px) suited for desktop or mobile Canvas views.

Installation & Deployment
Method 1: Direct Canvas Page Embed (Recommended)
Navigate to your target Canvas course and create or edit a Page.

Click the HTML Editor icon (</>) below the Rich Content Editor (RCE).

Paste the provided interactive HTML snippet.

Click the </> icon again to return to the Visual Editor.

Locate the placeholder dashed box: [ INSERT SCREENSHOT HERE ].

Highlight the placeholder text, select the Images icon on the Canvas toolbar, and upload your interface screenshot.

Click Save & Publish.

Method 2: Iframe Hosting (Isolated Environment)
Save the standalone HTML file locally as canvas-branching-scenario.html.

Upload the file to your Canvas course under Files (set visibility to "Only available with link").

Embed it into any Canvas page using the HTML editor:
