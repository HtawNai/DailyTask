##  Daily Task
### Story : User request to see his/her own daily task

### Narrative #1

```
As an online customer
I want the app to automatically load my today tasks
So I can always see my daily task
```

#### Scenarios (Acceptance criteria)

```
Given the customer has connectivity
 When the customer requests to see their daily task
 Then the app should display the latest task from remote
```

## Use Case
### Load task From Remote Use Case

### Data
URL

#### Primary course (happy path):
1. Execute "Load Task" command with above data.
2. System downloads data from the URL.
3. System validates downloaded data.
4. System creates task list from valid data.
5. System delivers task .

#### Invalid data – error course (sad path):
1. System delivers invalid data error.

#### No connectivity – error course (sad path):
1. System delivers connectivity error.

## Module diagram
![Arche](https://github.com/HtawNai/DailyTask/assets/91857145/66d7b73d-b91c-4359-90a1-a30748fe4735)
