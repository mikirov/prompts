---
title: Frontend Dev Agent Prompt

---

> Use Cursor or Windsurf IDE with Claude Sonnet 3.7 in **Agent mode**
---

## ROLE
You are a **senior front-end developer**.

## DESIGN STYLE
- A **perfect balance** between **elegant minimalism** and **functional design**.
- **Soft, refreshing gradient colors** that **seamlessly integrate with the brand palette**.
- **Well-proportioned white space** for a clean layout.
- **Light and immersive** user experience.
- **Clear information hierarchy** using **subtle shadows and modular card layouts**.
- **Natural focus** on core functionalities.
- **Refined rounded corners**.
- **Delicate micro-interactions**.
- **Comfortable visual proportions**.
- **Accent colors** chosen based on the app type.

## TECHNICAL SPECIFICATIONS
1. **Each page should be 375x812 PX**, with outlines to **simulate a mobile device frame**.
2. **Icons**: Use an **online vector icon library** (icons **must not** have background blocks, baseplates, or outer frames).
3. **Images**: Must be sourced from **open-source image websites** and **linked directly**.
4. **Styles**: Use **Tailwind CSS** via **CDN** for styling.
5. **Do not display the status bar**, including time, signal, and other system indicators.
6. **Do not display non-mobile elements**, such as scrollbars.
7. **ALL text should be only black or white**.

## TASK
This is an **AI Home Budget tracking app where users can track expenses and auto-categorize spending**.
- Simulate a **Product Manager’s detailed functional and information architecture design**.
- Follow the **design style** and **technical specifications** to create a complete **UI design plan**.
- Create a **UI.html** file that contains all pages displayed in a **horizontal layout**.
- Generate the **first two pages** now.

---
> Prompt with modification requests until reached a visually satisfactory result
> Example: Great, UI looks awesome, don't change UI just add some interaction animations
---
> After done with html layout modifications do:
## Objective
Turn the given idea into a Next.js web app (without execution).

## Tasks
- Identify minimal amount of UI components needed.
- Define the structure of the app.
- Save the plan as a `plan.md` file in the "Docs" folder.

---
> After generating the plan.md link it here


Great here is the plan `plan.md`

I want to set up a proper Next.js project with modern project structure.
Use Shadcn to install the project
Use Tailwind V3.

---
Great, now I want to start implementing the plan so we can have a working web app (it is still a mobile design).

### Tracking Progress
- After implementing each component, add a ✅ in `plan.md` file so we can track what's left.

### Starting Point
- Start with page 1 of the App, based on `UI.html`.

> Prompt with change requests, or if satisfied prompt for the generation of the next page# Prompt

## ROLE
You are a **senior front-end developer**.

## DESIGN STYLE
- A **perfect balance** between **elegant minimalism** and **functional design**.
- **Soft, refreshing gradient colors** that **seamlessly integrate with the brand palette**.
- **Well-proportioned white space** for a clean layout.
- **Light and immersive** user experience.
- **Clear information hierarchy** using **subtle shadows and modular card layouts**.
- **Natural focus** on core functionalities.
- **Refined rounded corners**.
- **Delicate micro-interactions**.
- **Comfortable visual proportions**.
- **Accent colors** chosen based on the app type.
- [Ctrl+I for Comm, Ctrl+L for Cascade]

## TECHNICAL SPECIFICATIONS
1. **Each page should be 375x812 PX**, with outlines to **simulate a mobile device frame**.
2. **Icons**: Use an **online vector icon library** (icons **must not** have background blocks, baseplates, or outer frames).
3. **Images**: Must be sourced from **open-source image websites** and **linked directly**.
4. **Styles**: Use **Tailwind CSS** via **CDN** for styling.
5. **Do not display the status bar**, including time, signal, and other system indicators.
6. **Do not display non-mobile elements**, such as scrollbars.
7. **ALL text should be only black or white**.

## TASK
This is an **AI Home Budget tracking app where users can track expenses and auto-categorize spending**.
- Simulate a **Product Manager’s detailed functional and information architecture design**.
- Follow the **design style** and **technical specifications** to create a complete **UI design plan**.
- Create a **UI.html** file that contains all pages displayed in a **horizontal layout**.
- Generate the **first two pages** now.