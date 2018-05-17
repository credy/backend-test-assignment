# Credy

## Backend developer position's test tasks (choose one)

------------------------------------------------------------------------------------------------------------------------

### Task 1: Write an application in Yii2 called “Group Blog”.

**Description**

There are people who can post text, image, video posts into the blog.  Also there should be user-friendly interface to manage the posts and users. Anonymous users should have possibility to leave their comments.

### Task 2: Write an application in Yii2 called “Warehouse”.

**Description**

There is warehouse with many employees who can add/edit/delete products to stock. Also there are many categories of products. Such case is possible that one product belongs to many categories. Product should contain picture, description, price and whatever.

#### Roles & users setup description (for senior level)

There are 2 groups: users & admins. 

* Admins:  can invite (add) other people to the group and manage users; can edit all the content (full access to everything)
* Users:  can edit only their own content

------------------------------------------------------------------------------------------------------------------------

## Scoring & review

Please use github.com to publish your application. When its finished, drop us a link. It will be reviewed by our developers & you will be given feedback taking into account the table below.

| Max points | Topic | Entry level | Middle level | Senior developer |
|:----------:|---------------------------------------------------------------------------------------------------|-------------|--------------|------------------|
| 2 | Git usage <br><ul><li>explanatory commit messages</li><li>reasonable amount of functionality in a commit</li></ul> | X | X | X |
| 3 | Internationalization support <br><ul><li>handling plural forms</li> <li>no concatenations</li><li>proper number formatting</li></ul> |  | X | X |
| 2 | Yii’s built-in methods / helpers usage <br><ul><li>@alias</li><li>behaviours</li></ul> |  | X | X |
| 2 | Migrations <br><ul><li>separate migrations</li><li>full migrate up/down support</li></ul> |  | X | X |
| 2 | Documentation <br><ul><li>easy to follow documentation</li><li>MarkDown</li></ul> |  | X | X |
| 1 | Proper error handling |  |  | X |
| 1 | PHP compatibility from 5.6+ |  | X | X |
| 2 | Multiple database support <br><ul><li>supports SQL databases</li><li>supports noSQL databases</li></ul> |  |  | X |
| 1 | Optimal memory usage |  |  | X |
| 1 | Optimal DB usage |  |  | X |
| 1 | Using query objects |  |  | X |
| 1 | Caching & cache invalidation [clicky :)](https://martinfowler.com/bliki/TwoHardThings.html)  |  |  | X |
| 1 | Access control <br><ul><li>proper usage of RBAC</li></ul> |  |  | X |
| 2 | Automated tests <br><ul><li>unit</li><li>functional</li><li>acceptance (bonus point)</li></ul> |  |  | X |
