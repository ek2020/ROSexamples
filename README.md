ROS Examples
============

This repository is a personal collection of small ROS (Resource Orchestration Service) examples. ROS is Alibaba Cloud's resource orchestration language, similar to AWS CloudFormation. You can learn more about ROS in the [Alibaba Cloud ROS documentation](https://www.alibabacloud.com/help/doc-detail/28852.htm).

Contents
========

Each example script is stored in a .json file. Each script has its own folder, so that I can group the script, any dependencies (such as base64 encoded commands for machines to run at start), and its readme and related diagrams. 

Currently the layout looks something like this:

```
.
├── LICENSE
├── README.md
└── chrome-on-windows
    ├── README.md
    ├── chrome-on-windows.json
    ├── diagrams
    │   ├── chrome_on_windows.png
    │   └── chrome_on_windows.xml
    ├── install_chrome.b64
    └── install_chrome.ps1
```

Usage
=====

All you need to do to run these examples is to open up the .json file for the ROS script you are interested in, and then copy-paste it into the "Create Template" dialog in the ROS console. Once you've created a new template, you can click "Create Stack" next to your template in the Alibaba Cloud ROS console to create the resources defined in the template. It's that easy!

You could, technically, use terraform to deploy or create ROS templates as well. In the future I may cover that in my [terraformExamples](https://github.com/jeremypedersen/terraformExamples) repository.

License
=======

This repository is licensed under "The Unlicense" so feel free to use the content here in any way you like.