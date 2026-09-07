# Manual Test Cases – Code Editor Live

**Author:** Zahid Shaikh  
**Maintainer:** PW Institute of Innovation – Open Source

## UI Load Tests
- [ ] Application loads without console errors
- [ ] Editor UI renders correctly on page load
- [ ] Default HTML, CSS, and JS content is visible
- [ ] Save & Load JSON works

## Editor Functionality
- [ ] HTML editor updates preview correctly
- [ ] CSS editor updates preview styling
- [ ] JavaScript editor executes code correctly
- [ ] Errors are shown in the Output panel

## Preview Behavior
- [ ] Preview auto-updates after code changes
- [ ] "Run" button forces preview update
- [ ] "Open preview in new window" works

## Theme & Font Controls
- [ ] Theme switch changes editor theme
- [ ] Font size increase works
- [ ] Font size decrease works
- [ ] Settings persist after reload

## Save & Load
- [ ] Project saves as JSON file
- [ ] Saved file reloads correctly
- [ ] Local storage restore works after refresh
- [ ] Indicator shows "Saved" on initial load
- [ ] Editing HTML changes the status to "Unsaved changes"
- [ ] Editing CSS changes the status to "Unsaved changes"
- [ ] Editing JavaScript changes the status to "Unsaved changes"
- [ ] Editing the assignment / tests fields changes the status to "Unsaved changes"
- [ ] Clicking the Save button changes the status to "Saved" after a successful save
- [ ] Cmd / Ctrl + S saves and changes the status to "Saved"
- [ ] Loading a project restores the "Saved" status
- [ ] Initializing a project restores the "Saved" status
- [ ] Refresh / load does not incorrectly show unsaved changes

## Keyboard Shortcuts
- [ ] Ctrl / Cmd + Enter runs code
- [ ] Ctrl / Cmd + S saves project

## Adaptive Layout Modes
- [ ] Layout switcher (Split / Stack / Focus) is visible in the header
- [ ] Split view shows editors and preview side by side, output on the right
- [ ] Stacked view flows vertically: editors, then preview, then output
- [ ] Focus mode shows a single panel at a time (Code / Preview / Output)
- [ ] Focus switcher appears only in Focus mode
- [ ] Ace editors resize correctly during layout transitions
- [ ] Chosen layout persists after page reload
- [ ] Focus panel persists after page reload
- [ ] First visit on a narrow viewport defaults to Stacked mode

## Cross-Browser
- [ ] Works in Chrome
- [ ] Works in Edge
- [ ] Works in Firefox
