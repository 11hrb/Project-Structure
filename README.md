simple-task-manager/
├── app/
│   ├── controllers/
│   │   └── tasks_controller.rb
│   ├── models/
│   │   └── task.rb
│   ├── views/
│       └── tasks/
│           ├── index.html.erb
│           ├── new.html.erb
│           └── edit.html.erb
├── config/
│   └── routes.rb
├── db/
│   ├── migrate/
│   │   └── create_tasks.rb
├── features/      # ➡️ Cucumber BDD tests
│   ├── step_definitions/
│   ├── support/
│   └── manage_tasks.feature
├── spec/          # ➡️ RSpec Unit Tests
│   ├── models/
│   │   └── task_spec.rb
│   ├── controllers/
│   │   └── tasks_controller_spec.rb
├── README.md
├── Gemfile
├── Rakefile
├── config.ru
├── Procfile (for Heroku, optional)
└── ...
