# Web Content Accessibility Guidelines (WCAG) 2.2

## Hierarchy

1. Principles
2. Guidelines
3. Success Criteria
4. Sufficient and Advisory Techniques

---

Level A

# Perceivable

## Guideline 1.1 Text Alternatives

### 1. Success Criterion 1.1.1 Non-text Content

- All non-text content that is presented to the user has a text alternative that serves the equivalent purpose, except for the situations listed below.

## Guideline 1.2 Time-based Media

### 2. Success Criterion 1.2.1 Audio-only and Video-only (Prerecorded)

- For prerecorded audio-only and prerecorded video-only media, the following are true, except when the audio or video is a media alternative for text and is clearly labeled as such:
  - Prerecorded Audio-only 
    - An alternative for time-based media is provided that presents equivalent information for prerecorded audio-only content.
  - Prerecorded Video-only
    - Either an alternative for time-based media or an audio track is provided that presents equivalent information for prerecorded video-only content.

### 3. Success Criterion 1.2.2 Captions (Prerecorded)

- Captions are provided for all prerecorded audio content in synchronized media, except when the media is a media alternative for text and is clearly labeled as such.

### 4. Success Criterion 1.2.3 Audio Description or Media Alternative (Prerecorded)

- An alternative for time-based media or audio description of the prerecorded video content is provided for synchronized media, except when the media is a media alternative for text and is clearly labeled as such.

## Guideline 1.3 Adaptable

### 5. Success Criterion 1.3.1 Info and Relationships

- Information, structure, and relationships conveyed through presentation can be programmatically determined or are available in text.

### 6. Success Criterion 1.3.2 Meaningful Sequence

- When the sequence in which content is presented affects its meaning, a correct reading sequence can be programmatically determined.

### 7. Success Criterion 1.3.3 Sensory Characteristics

- Instructions provided for understanding and operating content do not rely solely on sensory characteristics of components such as shape, color, size, visual location, orientation, or sound.

## Guideline 1.4 Distinguishable

### 8. Success Criterion 1.4.1 Use of Color

- Color is not used as the only visual means of conveying information, indicating an action, prompting a response, or distinguishing a visual element.

### 9. Success Criterion 1.4.2 Audio Control

- If any audio on a web page plays automatically for more than 3 seconds, either a mechanism is available to pause or stop the audio, or a mechanism is available to control audio volume independently from the overall system volume level.

# Operable

## Guideline 2.1 Keyboard Accessible

### 10. Success Criterion 2.1.1 Keyboard

- All functionality of the content is operable through a keyboard interface without requiring specific timings for individual keystrokes, except where the underlying function requires input that depends on the path of the user's movement and not just the endpoints.

### 11. Success Criterion 2.1.2 No Keyboard Trap

- If keyboard focus can be moved to a component of the page using a keyboard interface, then focus can be moved away from that component using only a keyboard interface, and, if it requires more than unmodified arrow or tab keys or other standard exit methods, the user is advised of the method for moving focus away.

### 12. Success Criterion 2.1.4 Character Key Shortcuts

- If a keyboard shortcut is implemented in content using only letter (including upper- and lower-case letters), punctuation, number, or symbol characters, then at least one of the following is true:
  - Turn off
    - A mechanism is available to turn the shortcut off;
  - Remap
    - A mechanism is available to remap the shortcut to include one or more non-printable keyboard keys (e.g., Ctrl, Alt);
  - Active only on focus
    - The keyboard shortcut for a user interface component is only active when that component has focus.

## Guideline 2.2 Enough Time

### 13. Success Criterion 2.2.1 Timing Adjustable

- For each time limit that is set by the content, at least one of the following is true:
  - Turn off
    - The user is allowed to turn off the time limit before encountering it; or
  - Adjust
    - The user is allowed to adjust the time limit before encountering it over a wide range that is at least ten times the length of the default setting; or
  - Extend
    - The user is warned before time expires and given at least 20 seconds to extend the time limit with a simple action (for example, "press the space bar"), and the user is allowed to extend the time limit at least ten times; or
  - Real-time Exception
    - The time limit is a required part of a real-time event (for example, an auction), and no alternative to the time limit is possible; or
  - Essential Exception
    - The time limit is essential and extending it would invalidate the activity; or
  - 20 Hour Exception
    - The time limit is longer than 20 hours.

### 14. Success Criterion 2.2.2 Pause, Stop, Hide

- For moving, blinking, scrolling, or auto-updating information, all of the following are true:
  - Moving, blinking, scrolling
    - For any moving, blinking or scrolling information that (1) starts automatically, (2) lasts more than five seconds, and (3) is presented in parallel with other content, there is a mechanism for the user to pause, stop, or hide it unless the movement, blinking, or scrolling is part of an activity where it is essential; and
  - Auto-updating
    - For any auto-updating information that (1) starts automatically and (2) is presented in parallel with other content, there is a mechanism for the user to pause, stop, or hide it or to control the frequency of the update unless the auto-updating is part of an activity where it is essential.

## Guideline 2.3 Seizures and Physical Reactions

### 15. Success Criterion 2.3.1 Three Flashes or Below Threshold

- Web pages do not contain anything that flashes more than three times in any one second period, or the flash is below the general flash and red flash thresholds.

## Guideline 2.4 Navigable

### 16. Success Criterion 2.4.1 Bypass Blocks

- A mechanism is available to bypass blocks of content that are repeated on multiple web pages.

### 17. Success Criterion 2.4.2 Page Titled

- Web pages have titles that describe topic or purpose.

### 18. Success Criterion 2.4.3 Focus Order

- If a web page can be navigated sequentially and the navigation sequences affect meaning or operation, focusable components receive focus in an order that preserves meaning and operability.

### 19. Success Criterion 2.4.4 Link Purpose (In Context)

- The purpose of each link can be determined from the link text alone or from the link text together with its programmatically determined link context, except where the purpose of the link would be ambiguous to users in general.

## Guideline 2.5 Input Modalities

### 20. Success Criterion 2.5.1 Pointer Gestures

- All functionality that uses multipoint or path-based gestures for operation can be operated with a single pointer without a path-based gesture, unless a multipoint or path-based gesture is essential.

### 21. Success Criterion 2.5.2 Pointer Cancellation

- For functionality that can be operated using a single pointer, at least one of the following is true:
  - No Down-Event
    - The down-event of the pointer is not used to execute any part of the function;
  - Abort or Undo
    - Completion of the function is on the up-event, and a mechanism is available to abort the function before completion or to undo the function after completion;
  - Up Reversal
    - The up-event reverses any outcome of the preceding down-event;
  - Essential
    - Completing the function on the down-event is essential.

### 22. Success Criterion 2.5.3 Label in Name

- For user interface components with labels that include text or images of text, the name contains the text that is presented visually.

### 23. Success Criterion 2.5.4 Motion Actuation

- Functionality that can be operated by device motion or user motion can also be operated by user interface components and responding to the motion can be disabled to prevent accidental actuation, except when:
  - Supported Interface
    - The motion is used to operate functionality through an accessibility supported interface;
  - Essential
    - The motion is essential for the function and doing so would invalidate the activity.

# Understandable

## Guideline 3.1 Readable

### 24. Success Criterion 3.1.1 Language of Page

- The default human language of each web page can be programmatically determined.

## Guideline 3.2 Predictable

### 25. Success Criterion 3.2.1 On Focus

- When any user interface component receives focus, it does not initiate a change of context.

### 26. Success Criterion 3.2.2 On Input

- Changing the setting of any user interface component does not automatically cause a change of context unless the user has been advised of the behavior before using the component.

### 27. Success Criterion 3.2.6 Consistent Help

- If a web page contains any of the following help mechanisms, and those mechanisms are repeated on multiple web pages within a set of web pages, they occur in the same order relative to other page content, unless a change is initiated by the user:
  - Human contact details
  - Human contact mechanism
  - Self-help option
  - A fully automated contact mechanism

## Guideline 3.3 Input Assistance

### 28. Success Criterion 3.3.1 Error Identification

- If an input error is automatically detected, the item that is in error is identified and the error is described to the user in text.

### 29. Success Criterion 3.3.2 Labels or Instructions

- Labels or instructions are provided when content requires user input.

### 30. Success Criterion 3.3.7 Redundant Entry

- Information previously entered by or provided to the user that is required to be entered again in the same process is either:
  - auto-populated, or
  - available for the user to select.
- Except when:
  - re-entering the information is essential,
  - the information is required to ensure the security of the content, or
  - previously entered information is no longer valid.

# Robust

## Guideline 4.1 Compatible

### 31. Success Criterion 4.1.2 Name, Role, Value

- For all user interface components (including but not limited to: form elements, links and components generated by scripts), the name and role can be programmatically determined; states, properties, and values that can be set by the user can be programmatically set; and notification of changes to these items is available to user agents, including assistive technologies. 