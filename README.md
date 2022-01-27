# Tips for effective git

### 1. Issue 
#### Title


#### Body


#### Due date


### 2. Label
#### Divide the labels into categories 
Instead of flattening all labels, we could group them into categories: status, type, priority. The format for label now [MAIN-CATEGORY]_[SUB-CATEGORY]
- Status: `Status:Open`, `Status:In-Progress`, `Status:Pending`, `Status:Completed`, `Status: Delayed`
- Type: `Type:Feature`, `Type:Bug`, `Type:Refactor`, `Type:Hotfix`
- Priority: `Priority:Low`, `Priority:Normal`, `Priority:High`, `Priority:Critical`

#### Use semantic coloring
![Semantic coloring](./assets/Semantic-coloring.png)

- Use blue color (Informative) for `SUB_CATEGORY` like `Pending`
- Use green color (Positive) for `SUB_CATEGORY` like `Feature`, `Low`
- Use orage color (Notice) for `SUB_CATEGORY` like `In-Progress`, `Refactor`, `Normal`
- Use red color (Negative) for `SUB_CATEGORY` like `Delayed`, `High`, `Bug`, 'Hotfix'

Within each color, you can change color contrast to indicate different importance levels.
![Semantic colors](https://spectrum.adobe.com/static/images/color_semantic_desktop@2x_LNW6UD62tQ4a2LEbrcElu_1611634721087.png)

### 3. Branch naming
- Branch name should follow `Type` label and the format looks like this: `{feature, bug, refactor, hotfix}/[BRANCH_NAME]`
- Use lower case for branch naming
- Use hyphens (-) as separators
- Make sure that label type and branch name are semantically consistent
  - Type:Feature -> feature/proj-init
  - Type:Bug -> bug/proj-init
  - Type:Refactor -> refactor/proj-init
  - Type:Hotfix -> hotfix/proj-init

### 4. Commit message
- Use [sentence case](https://www.k-state.edu/grad/academics/etdr/write/sentence-case.html) capitalization



### 5. Merge request title
- Use [sentence case](https://www.k-state.edu/grad/academics/etdr/write/sentence-case.html) capitalization


### 6. Tag



### 7. Branching



## Reference
1. What is sentence case?. https://www.k-state.edu/grad/academics/etdr/write/sentence-case.html
2. Semantic colors. https://spectrum.adobe.com/page/color/

