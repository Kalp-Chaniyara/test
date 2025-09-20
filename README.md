# User Stories  

---

## User Story 24: Accessibility for Visually Impaired Users  

**Front**  
As a visually impaired user, I want to navigate the app using only audio cues, so I can use Manaska just like any other user.  

**Back**  
- All navigation must be accessible via keyboard controls and screen readers.  
- The user must be able to access all features without needing visual interaction.  
- The audio must be clear, understandable, and its volume and speed must be adjustable.  
- All responses (e.g., mind map generated, changes saved, syntax error) must be available in audio format.  
- `aria-label` and `aria-describedby` tags must be added in HTML where needed.  
- The solution must follow **WCAG accessibility guidelines and standards**.  

---

## User Story 25: Accessibility for Users Hard of Hearing  

**Front**  
As a user that is hard of hearing, I want to navigate the app without needing any audio cues, so I can use Manaska just like any other user.  

**Back**  
- If any audio feedback is provided by Manaska, it must include appropriate captions.  
- Users must be able to access the entire app without relying on audio cues.  

---

## User Story 26: Accessibility for Cognitively Impaired Users  

**Front**  
As a cognitively impaired user, I want the app to be easy to use by:  
- Having a layout with clear structure and hierarchy.  
- Sections with proper headings and descriptions.  
- Simple, easy-to-understand language.  
- Tooltips with explanations for elements on the screen.  
- Confirmation messages before performing drastic actions.  
So that I can use the app to its full potential.  

**Back**  
- The layout must use consistent headings and section schemes to organize content clearly.  
- All interactive elements must have accessible labels and tooltips describing their function.  
- Text content must be written in plain language, avoiding jargon and domain-specific terms.  
- Actions that delete or significantly alter data must prompt the user with a confirmation dialog before proceeding.  

---

## User Story 27: Accessibility for Color Blind Users  

**Front**  
As a color blind user, I want to specify which kinds of color schemes the system should use while generating the mind map, and I want to clearly read the text on the website, so I can use Manaska properly.  

**Back**  
- The LLM prompt must consider the user’s color preferences when generating the mind map.  
- Text and background must maintain sufficiently high contrast, following **WCAG guidelines**.  

---

## User Story 28: Comprehensive & Easy-to-Understand Documentation  

**Front**  
As a user, I want reference and guidance on all aspects of the app in the documentation, and I want it to be easy to understand.  

**Back**  
- The website must have extensive documentation explaining how to use features, with clearly listed steps and examples.  
- The language must be grammatically correct, simple, and easy to understand.  
- The documentation must have a clear structure, with closely related topics grouped together.  

---

## User Story 29: Feedback Providing  

**Front**  
As a user, I want to provide detailed feedback on what the app does well, what it does poorly, and what features I’d like to see in the future.  

**Back**  
- The website must include a feedback page where users can submit feedback directly to developers.  
- The website must provide a contact email for submitting feedback.  

---

## User Story 30: Error Handling & Support  

**Front**  
As a user, I want clear and helpful error messages when something goes wrong, so I can quickly understand and fix issues.  

**Back**  
- All potential errors must be handled gracefully with explanations of what went wrong and how to resolve it.  
- A help section or support link must be easily accessible during issues.  

---

## User Story 31: Security & Privacy  

**Front**  
As a privacy-conscious user, I want my data to be secure and handled transparently, so I can trust the app with my sensitive information.  

**Back**  
- Users must be informed about data collection, storage, and usage.  
- Mind maps and personal data must be encrypted during storage and transmission.  
- Users must be able to easily delete their data.  
- Users must be notified and explicitly consent before any third-party cookies or tracking tools are set.  

---

## User Story 32: Personal Dashboard for Recent Maps & Favorites  

**Front**  
As a user, I want a dashboard showing my recently generated maps and favorite charts, so I can quickly resume my work without searching through old files.  

**Back**  
- The dashboard must display:  
  - A list/grid of recently created or edited maps/charts (with timestamps).  
  - A section for favorites, pinned by the user.  
- Each dashboard item must include:  
  - Map/Chart title.  
  - Thumbnail or preview.  
  - Date of last update.  
- Users must be able to:  
  - Click an item to open it directly.  
  - Pin/unpin maps to/from favorites.  
  - Sort and filter items (e.g., by date modified, alphabetical order, type).  
- The dashboard must load automatically upon login as the home screen.  
- A clear **“Create New Map”** button must be visible.  
- Autosave must ensure recently generated maps always appear without manual saving.  

---

## User Story 33: Responsive Mobile Web Support  

**Front**  
As a user, I want the website to be fully responsive and accessible on my phone, so I can create and edit mind maps on the go without needing a separate app.  

**Back**  
- The website layout must automatically adjust for different screen sizes (desktop, tablet, mobile).  
- Core desktop features must also be usable on mobile:  
  - Creating mind maps from text prompts.  
  - Adding, removing, renaming, and moving nodes.  
  - Viewing recent and favorite maps.  
  - Saving and syncing maps with the cloud.  
- UI must be touch-friendly:  
  - Large tap targets for buttons and menus.  
  - Swipe gestures for interactions (e.g., opening/closing sidebars).  
  - Collapsible menus and simplified toolbars for small screens.  

---
