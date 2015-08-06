# Mini Lessons Homework

For each of the following topics, please answer each of the questions
in an issue on this repository.

## Has many Through

- [screencast](https://www.youtube.com/watch?v=JxW8lJzLhxI)

### Questions

1. What is the role of a join table in a many-to-many relationship
2. What two columns must be present in a join table?
3. Given the example below, edit the code to define a has many :through relationship.
    ```ruby
    class Customer < ActiveRecord::Base
    end

    class Product < ActiveRecord::Base
    end

    class Purchase < ActiveRecord::Base
    end
    ```
4. Based on #3, give an example of associating two instances via the join model.

Note: For #3 and #4, you can answer these questions by including link(s) to places in your Project 2 repo where you do the requested tasks. Make sure you're liking to a specific file / line in that file. [How to link to line numbers in github](http://stackoverflow.com/questions/23821235/how-to-link-to-specific-line-number-on-github)

## Devise

[Lesson Notes](https://github.com/ga-dc/pbj/tree/master/06-project-2/devise)
[Screencast](https://www.youtube.com/watch?v=h6na4saDPaA&index=1&list=PLnKff2cv2ktb8QWH77oI-Gb0TnbdiHKL0)

### Questions
1. What does the `current_user` method that the Devise gem provides?

2. What does the `authenticate_user!` method that the Devise gem provides?

3. Write a signout link using the `link_to` rails helper and a devise path.

4. How do I generate a devise model in the terminal?

5. What are the trade offs for using a gem for authentication over a handrolled solution? (no real right answer)


## Validations

- [screencast](#)

### Questions
