# my-desktop-calendar
What’s new:

    Bigger calendar
        Larger grid cells (h-32), larger text, wider layout (max-w-7xl).
    Attach images, videos, and files
        Drag & drop into the “Attachments” area when adding a task, or click “browse.”
        Previews:
            Images: inline thumbnails
            Videos: inline playable previews
            Other files: listed with download/open link
        Persistence:
            Small files (<= 2MB) are embedded and persist across reloads.
            Large files are “linked” using a local object URL (works this session; reattach after reload if needed).
    Connect with local files
        Works via drag & drop or the file picker (browser security requires user selection).
    Labels and filtering
        Add custom labels (name + color).
        Assign labels to tasks (“+ Label” on each task).
        Filter the day’s list by one or more labels.
    Drag-and-drop
        Reorder tasks within a day by dragging them up/down.
        Move tasks to another date by dragging a task and dropping it on a calendar day cell.
    Reminder time persists
        Daily reminder time is saved; popup notifies you when there are tasks.

How to use it:

    Add task: Select a date -> Add -> type title -> optionally drag/drop files -> Save.
    Assign labels: On a task, click “+ Label” -> toggle labels.
    Move tasks: Drag a task onto another date in the calendar.
    Reorder tasks: Drag a task above/below another in the list.
    Filter: Click labels at the top of the sidebar to filter today’s tasks.

Notes and limits:

    For privacy/security, browsers can’t auto-scan your drive; files must be chosen or dropped by you.
    Large files are session-only previews (link expires after reload). The app tells you if a link is unavailable and lets you reattach.
    Small files (<= 2MB) are embedded and persist in local storage.

Want desktop notifications (system-level toasts) as well? I can add the browser Notification API prompt and show alerts even when the tab isn’t focused.
