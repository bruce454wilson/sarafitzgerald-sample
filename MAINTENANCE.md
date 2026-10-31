# Keeping the site up to date

There are two ways to make changes. Either way, the site rebuilds by itself about a minute after a change is saved.

## Option A: Pages CMS (recommended for Sara)

1. Go to **app.pagescms.org** and sign in with GitHub. The first time, approve access to this repository.
2. Pick the site. The left side shows three sections: **Events**, **Book pages** and **Other pages**.
3. Make the change and click **Save**.

### Add an event
Events → **Add an entry** → fill in:
- **Event name**, for example `Chautauqua Institution, 2027 Season`
- **Link** (optional), the event's web page
- **Date**: the first day of the event. It's used only for sorting. After that date passes, the event moves from "Upcoming" to "Past appearances" by itself.
- **Details**: the lines shown under the name, exactly as typed. A blank line starts a new paragraph.

New events can be added anywhere in the list, because the site sorts them by date.

### Change wording on a page
Book pages or Other pages → pick the page → edit in the text box (it has Bold, Italic, Link and Image buttons) → Save.

### Add a photo
In any text box, use the Image button and upload the file. It's stored in `assets/images`.

### Add a new book
Book pages → **Add an entry** → title, subtitle, cover image and position in the list (1 = first), then the page text. It shows up in the "My Books" menu and on the books grid by itself.

## Option B: edit on github.com

Every page is a text file. Open it on github.com, click the pencil icon, edit, and click **Commit changes**.
- Events: `_data/events.yml`
- Book pages: `_books/`
- Everything else: `_pages/`
- The menu: `_data/nav.yml`

## Things that need someone technical
- Changing fonts, colors or layout (`assets/css/site.css` and `_layouts/`).
- Adding a new item to the top menu (`_data/nav.yml`).
- The domain name and the contact-form connection.

## What Sara no longer has to do
- Move events from upcoming to past.
- Update the blog list on the home page, which reads the latest posts from her WordPress.com blogs by itself.
- Pay a monthly site-builder fee. GitHub Pages hosting is free. The domain renewal stays with GoDaddy.
