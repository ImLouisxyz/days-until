# Days Until Countdown

This project is a simple responsive web page that displays any (reasonable) number countdown timers.  
Each timer shows the number of days remaining until a specific preset date.  
The page is optimized for landscape display and includes a fullscreen mode.

---

## Features

- Dark mode
- Independent countdowns, each showing days until a given date
- Click a timer to expand it fullscreen; click again to return to all timers
- Optional fullscreen button for the entire site (button hides when active)
- Updates automatically at midnight
- Fully responsive layout for different screen sizes

---

## Editing Timers

Each timer is defined in index.html with a `data-date` attribute:

```html
<div class="timer" data-date="2025-12-25">
  <div class="title">Christmas 2025</div>
  <div class="days">?</div>
</div>
```

To change the countdowns:

Edit the data-date value to your target date (YYYY-MM-DD format).

Update the text inside .title to describe the event.

You can add or remove timers by duplicating or deleting these blocks inside the container.

---

## Hosting on GitHub Pages

If you want to publish your own version of this site:

Fork this repository on GitHub.

Go to your fork’s Settings → Pages.

Under “Source”, select the branch you want to publish (usually main).

Select the root (/) directory and click Save.

After a short delay, your site will be available at:

`https://<your-username>.github.io/<repository-name>/`

Any changes you commit to your fork will appear automatically on your GitHub Pages site.

---

## Notes

The page is intended for landscape use, such as on monitors or wall displays.

The timers use the local time zone of the device displaying the page.
