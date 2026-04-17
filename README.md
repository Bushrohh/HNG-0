Edit mode — clicking Edit swaps the card content for a form with title, description, priority dropdown and due date inputs. Save updates the card live, Cancel restores everything. Focus returns to the Edit button when closed.
Status control — the static status badge is now a dropdown (<select>) letting you switch between Pending, In Progress and Done. It stays synced with the checkbox in both directions.
Priority indicator — a small colored dot sits next to the title (data-testid="test-todo-priority-indicator"). It changes color alongside the badge — green for Low, orange for Medium, red for High. The left border accent also updates.
Expand/collapse — description longer than 100 characters collapses with a fade and shows a "Show more" button. Clicking it expands, clicking again collapses. Uses aria-expanded and aria-controls as required.
Overdue indicator — a red "Overdue" pill badge (data-testid="test-todo-overdue-indicator") appears next to the time remaining when the task is past its due date.
Time stops when Done — when status is Done (via checkbox or dropdown), the time remaining stops updating and shows "Completed" instead.
