
# `top` – Real Time Process Monitoring

The **top** command in Linux is a **real-time monitoring** tool that provides a **dynamic view** of your system's **processes and resource usage**.

---

### Help and General Settings

- Help screen
  
  ```
  ?
  ```
  
  **Output:**
  Displays a help window listing all available keyboard shortcuts.
  
  **Purpose:**
  To quickly view all commands inside top.

- Quit top

  ```
  q
  ```
  
  **Output:**
  Exits top and returns to the shell.
  
  **Purpose:**
  To leave the top interface.

---

### Toggles (Headers and CPU View)

- Toggle load average line
  
  ```
  l
  ```
  
  **Output:**
  Shows or hides the load average line (1m/5m/15m).
  
  **Purpose:**
  To reduce or expand displayed system information.

- Toggle task summary line

  ```
  t
  ```
  
  **Output:**
  Shows or hides the tasks summary line.
  
  **Purpose:**
  To simplify the screen or show more task details.

- Toggle memory usage line

  ```
  m
  ```
  
  **Output:**
  Shows or hides memory and swap usage lines.
  
  **Purpose:**
  To reduce clutter or focus on CPU/process info.

- Toggle CPU single/per-core view

  ```
  1
  ```
  
  **Output:**
  Switches between one combined CPU line or multiple per-CPU lines.
  
  **Purpose:**
  To monitor CPU usage per core when needed.

---

### Refresh and Display Settings

- Change refresh rate

  ```
  s
  ```
  
  **Output:**
  Prompts for a new refresh interval in seconds.
  
  **Purpose:**
  To change how frequently top updates.

---

### Highlighting Options

- Enable/Disable Reverse Highlighting for Running Processes
  
  ```
  b
  ```
  
  **Output:**
  Enables/disables reverse highlighting for running processes.
  
  **Purpose:**
  To easily spot active processes.
  
- Enable Bold Headers and Running Processes
  
  ```
  B
  ```
  
  **Output:**
  Headers and running processes appear in bold.
  
---

### Thread Management

- Toggle Between Process and Thread View
  
  ```
  H
  ```
  
  **Output:**
  Switches between process-only view and per-thread view.

---

### Filtering and Sorting

- Filter Processes by User

  ```
  u
  ```
  
  **or**
  
  ```
  U
  ```


  - Prompts for a username:
  
    Username to filter by: `broy`

  
    **Output:**
    Then shows only that user’s processes.

- Sort by Memory Usage
  
  ```
  M
  ```
  
  **Output:**
  Sorts processes by memory usage (descending).
  
- Sort by CPU Usage
  
  ```
  P
  ```
  
  **Output:**
  Sorts processes by CPU usage (descending).

---

### Process Management

- Kill a process
  
  ```
  k
  ```
  
  **Output:**
  Prompts for PID and optional signal.
  
- Renice a process (Change Priority)
  
  ```
  r
  ```
  
  **Output:**
  Prompts for PID and nice value.
  
  **Purpose:**
  To adjust process priority.

---

### Customization

- Manage Columns (Fields)
  
  ```
  f
  ```
  
  **Output:**
  Opens field management menu for adding/removing/reordering columns.

- Save Current Top Configuration

  ```
  W
  ```
  
  **Output:**
  Saves current settings to `~/.toprc`.

---

