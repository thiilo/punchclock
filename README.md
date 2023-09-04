# `punchclock`

`punchclock` is a minimal project timer designed to quickly record work hours or any other time spent.
Add a project, clock in, and when you're done, clock out.

### Basic UI and `clocked in`
<img src="res/ui.png">

### Keyboard Shortcuts

- `Ctrl` + `A` to open `+ Add Project` dialogue
- `Esc` and `Enter` to cancel or save new project
- `Space` to clock in/clock out

projects and time spent are stored via `localStorage`, making the app as small as the `index-file` and `jquery` (currently just 98KB).

Icons are from [Phosphor Icons](https://phosphoricons.com/).

## development roadmap

As a personal project, `punchclock` is not too high on my agenda, but over time I'd like to add:

- [x] keyboard shortcuts
- [x] customized color schemes
- [ ] A timing log, storing session lengths and enabling deeper statistics
- [ ] Deeper Statistics
	- [ ] time spent daily, weekly, monthly
	- [ ] project distribution
- [ ] Exporting log files
	- [ ] work report card
