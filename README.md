# Lab 8: Capstone – Add Specs to an Existing Project

For this capstone, you will return to one of your past Ruby or Rails projects and add a full test suite using RSpec.

**Make sure you have Ruby (and Rails, if applicable) installed and run `bundle install` before starting this lab.**

## Step-by-Step Workflow

1. **Familiarize yourself with your Ruby or Rails project.**
2. If your project does not already use RSpec, add it to your Gemfile and run `bundle install`. For Rails projects, add `rspec-rails` and `factory_bot_rails` as well.
3. Create a `spec/student/` directory in your project to keep your specs organized, just like in previous labs.
4. Start with a small, manageable part of your project (e.g., one model or feature) and write specs for it first. Then expand coverage to other parts.
5. Write a comprehensive suite of specs, including:
   - **Model specs:** Test validations and associations. Use FactoryBot for test data if working with Rails.
   - **Request specs:** For Rails apps, test API endpoints or controllers.
   - **System/feature specs:** For Rails apps, use Capybara to test user-facing features.
6. Run `bin/rspec` or `rspec` frequently to check your progress and see which specs pass or fail.
7. Organize your specs for readability and maintainability. Use a variety of matchers and spec types as covered in previous labs.
8. Review the grading criteria below.

## Grading Criteria

- Breadth of coverage (all major features tested)
- Correct use of RSpec matchers
- Readability and organization of specs

## Resources

- [RSpec Documentation](https://rspec.info/documentation/)
