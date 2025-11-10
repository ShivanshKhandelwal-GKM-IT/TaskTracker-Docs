# Use Case Documentation

---
## Business Use Cases

| **Use Case** | **Business Value** |
|--------------|------------------|
| **Personal Task Management** | - Helps individuals stay organized and focused on daily priorities.<br>- Reduces the chance of forgetting important tasks.<br>- Encourages consistent productivity habits. |
| **Goal Tracking** | - Improves time management and goal tracking.<br>- Reduces procrastination by providing actionable to-do tasks.<br>- Increases motivation through visible task tracking. |
| **Cross-Device Task Synchronization** | - Enables consistent experience across devices.<br>- Increases convenience for users switching between phone and computer.<br>- Ensures data reliability and keeps tasks up to date. |
| **Offline Productivity Management** | - Ensures uninterrupted productivity.<br>- Reduces dependency on constant internet connectivity.<br>- Enhances user trust through reliability in all conditions. |
| **Daily Planning and Habit Building** | - Encourages personal discipline and accountability.<br>- Helps users visualize daily achievements.<br>- Supports habit formation through repetition and visibility. |

---
## Technical Use Cases

### Use Case 1: User Registration

| **Field** | **Description** |
|------------|----------------|
| **Actors** | New User |
| **Precondition** | User is not registered |
| **Trigger** | Tap **Sign Up** |
| **Main Flow** | 1. User enters **email** and **password**.<br>2. Application creates an account.<br>3. User is redirected to login page. |
| **Postcondition** | Account created successfully. |

---

### Use Case 2: Login

| **Field** | **Description** |
|------------|----------------|
| **Actors** | Registered User |
| **Precondition** | Account already exists |
| **Trigger** | Tap **Login** |
| **Main Flow** | 1. User enters credentials.<br>2. Application verifies credentials.<br>3. User session is activated.<br>4. User is redirected to the **Dashboard**. |
| **Postcondition** | Secure session is active. |

---

### Use Case 3: Add Task

| **Field** | **Description** |
|------------|----------------|
| **Actors** | Logged-in User |
| **Precondition** | User is authenticated |
| **Trigger** | Tap **Add Task** |
| **Main Flow** | 1. User fills **Task Title** and **Description**.<br>2. Task is saved and added.<br>3. UI updates in real time across devices. |
| **Postcondition** | Task is visible on all connected devices. |

---

### Use Case 4: Edit / Update Task

| **Field** | **Description** |
|------------|----------------|
| **Actors** | Logged-in User |
| **Precondition** | Task exists and belongs to the user |
| **Trigger** | Tap **Edit** |
| **Main Flow** | 1. Modal opens with pre-filled fields.<br>2. User edits details and taps **Save**.<br>3. UI refreshes instantly across devices. |
| **Postcondition** | Task is updated across all devices. |

---

### Use Case 5: Delete Task

| **Field** | **Description** |
|------------|----------------|
| **Actors** | Logged-in User |
| **Precondition** | Task exists and is owned by the user |
| **Trigger** | Tap **Delete** |
| **Main Flow** |1. A confirmation snackbar appears with an **Undo** option for 5 seconds.<br>2. If the user doesn’t undo within that time, the task is permanently deleted.<br>3. The task is then smoothly removed from the UI.|
| **Postcondition** | Task permanently deleted. |

---

## Use Case Diagram

![Task Tracker App Use Case Diagram](use case.png)

---

