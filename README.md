# UTExLMS
```
UTExLMS
│
├── Models (Chứa các class)
│   ├── Student.cs
│   └── Lecturer.cs
│
├── Views (Chứa các giao diện)
│   └── UserControlUTE
│       └── QuizView.xaml
├── ViewModels (Logic, kết nối dữ liệu hiển thị cho viwes, hành động như click..)
│   ├── MainViewModel.cs
│   ├── NavigationViewModel.cs (điều hướng các view)
│   └── BaseViewModel.cs (chức năng chung)
│
├── Commands
│   ├── RelayCommand.cs (Icommand)
│   └── NavigationCommand.cs (điều hướng giao diện bằng Icommand)
│
└── Resources (nguồn font, nuget...)
```
