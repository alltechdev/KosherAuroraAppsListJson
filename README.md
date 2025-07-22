# Kosher Aurora Apps List

This repository manages the master list of applications available in the Kosher Aurora Store, a modified version of the Aurora Store. The app list is controlled by the `apps_list.json` file in this repository.

## Purpose

The goal of this project is to provide a curated and specific list of applications suitable for a kosher-filtered environment. The app dynamically fetches this list to ensure that users always have access to an approved set of apps without needing to update the application itself.

---

## How to Contribute

We welcome contributions! If you would like to suggest a new app to be added to the store, please follow these steps:

1.  **Fork the Repository**: Create your own copy of this repository by clicking the "Fork" button at the top right of this page.
2.  **Edit the JSON File**: Navigate to the `apps_list.json` file in your forked repository. Use the edit button to add the package name of the app you want to suggest to the appropriate category. If a suitable category doesn't exist, you can create a new one.
3.  **Create a Pull Request**: Once you've made your changes, create a pull request. In your pull request, please provide a brief description of the app and explain why you believe it should be added to the list.

All pull requests will be reviewed. If the suggested app meets the criteria, your request will be accepted and merged into the master list.

---

### JSON File Format

When adding an app, please ensure you follow the correct format. The `apps_list.json` file contains a list of categories. Each category has a `title` and a list of app `packages`.

```json
{
  "categories": [
    {
      "title": "Category Name",
      "packages": [
        "com.example.app1",
        "com.example.app2"
      ]
    },
    {
      "title": "Another Category",
      "packages": [
        "com.example.anotherapp"
      ]
    }
  ]
}
```

Thank you for your interest and support in making the Kosher Aurora Store a great experience!
