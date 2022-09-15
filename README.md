# GitHub Copilot & GitHub Copilot Labs

## What is GitHub Copilot and Copilot Labs

As developers we write code and we want to it to be easy to read, efficient and maintainable. GitHub Copilot and Copilot labs are tools to make coding more efficient by providing code suggestions generated from GitHub repositories and Copilot labs as an plugin to provide experimental tools for developers.

![github-copilot-idea](https://user-images.githubusercontent.com/13942246/190413741-8399a9dd-1b38-4446-9d6a-0921f8e2e78b.jpeg)

### Technology behind Copilot

Keeping it short as I have no background in machine learning the GitHub copilot is powered by a deep neural network language model called Codex, which is based on the GPT-3 model. GPT-3 stands for the third generation of the Generative Pre-trained Transformer — a language model capable of generating sequences of text from simple prompts. Codex is derived from this model, which is capable not only of text, but also code generation in some of the most popular languages.

The model has been trained on public Github repositories which contain billions of lines of code, which some of it is good and most of it is just Hello World. The model has been trained to guess the missing symbols in code by learning about the structure and meaning of the code. 

## How to start using GitHub Copilot & Labs

GitHub Copilot is offered as a plugin in most common tools such as VS Code, Visual Studio, JetBrains and NeoVim. Github copilot settings that limit how GitHub can use the code you develop are configured on the GitHub settings page.

GitHub Labs is currently only available as VS Code plugin, Copilot license is needed to use this plugin

What is needed to start using Copilot & Labs
- GitHub Account
- GitHub Copilot free trial or subscription
- GitHub copilot plugin
- GitHub labs plugin

### Plugins

- Visual Studio Code 

[VS Code plugin documentation](https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-visual-studio-code)

[VS Code plugin link](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

- Visual Studio

[Visual Studio plugin documentation](https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-visual-studio)

[Visual studio plugin link](https://marketplace.visualstudio.com/items?itemName=GitHub.copilotvs)

- JetBrains

[JetBrains plugin documentation](https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-a-jetbrains-ide)

[JetBrains plugin link](https://plugins.jetbrains.com/plugin/17718-github-copilot)

- Neovim

[Neovim plugin documentation](https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-neovim)

[Neovim plugin link](https://github.com/github/copilot.vim)

- GitHub Copilot Labs

[Copilot Labs documentation](https://githubnext.com/projects/copilot-labs/)

[Copilot Labs link](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-labs)

### Pricing

- Free 60-day trial
- Monthly subscription 10$
- Yearly subscription 100$

## Why use GitHub Copilot

Coding is in the end doing many of the same features again and again with different logic, so why not reduce the boring stuff to the minimum. When developing with the Copilot I enjoyed the speed of the development and the low downtime needed to think what the next syntax should be and I could only focus on the logic of the app and what I wanted to achieve with it. When developing against new APIs someones has most likely done it before me so Copilot works in a way like a documentation that tells you what to do. Summarizing why to use copilot is that it makes coding more fun and efficient.

My personal findings go very much hand in hand with GitHubs own research on their developer productivity when using the Copilot. Developers using the Copilot felt they were more productive, completed code faster and overall felt more satisfied when coding. 

![copilot-benefits](https://user-images.githubusercontent.com/13942246/190413641-cbcde71c-8ac5-42f6-b5fd-b39c3e190bb9.jpeg)

So how does the Copilot exactly help you when coding? I've collected examples what I feel like are the key benefits of the Copilot. 

### Code suggestions

Like any current solution that gives code suggestions GitHub Copilot goes a step further and tries to give suggestions what could come next in your code and not just the next logical option from a predefined list.

Creating a React component

![copilot_auto_suggestion](https://user-images.githubusercontent.com/13942246/190413821-79ecb9fb-9d1b-47ea-ba97-2a4b866cfec3.gif)

Additional suggestions

![copilot_suggest_2](https://user-images.githubusercontent.com/13942246/190413981-c61bfc24-19d6-44ce-bac7-b91e60494ec6.gif)



### Code autocomplete

Copilot has the ability to some extend create full working sections of the code if given explanation what the code should achieve. This is limited by what the Copilot already knows of the code and how detailed the explanation is.

Creating Python function to get names of Pokemon.

![pokemon_api](https://user-images.githubusercontent.com/13942246/190414425-3462df02-3d50-4f3b-b12b-ba9dbe3541c7.gif)

Creating an array sorting function. The more data the Copilot has the better suggestions it can make.

![array_sort](https://user-images.githubusercontent.com/13942246/190414639-37da95a1-a40d-4e1d-bb96-88e366de1efa.gif)


### Testing

Copilot is able to automatically create test cases to cover cases that are described to it. 

Creating tests for Pokemon API

![pokemon_api_test](https://user-images.githubusercontent.com/13942246/190414772-49107ad8-3008-4f59-a2b0-a411e49a2751.gif)

Creating tests for array sorting function

![array_test_example](https://user-images.githubusercontent.com/13942246/190414878-63dce142-cecc-4065-87d2-f7945c7aebb2.gif)


### Reducing boring code

One of the best features is the Copilots ability to reduce the amount boring code or static variables that needs to be created manually. 

![cities_in_finland](https://user-images.githubusercontent.com/13942246/190414926-a6dafe23-023f-4092-b74f-bda31d6d7a0f.gif)


### Code translation and explanation

GitHub Copilot Labs that provides experimental tools to help you understand code or translate it to a different programming language. Especially the translation option provides good way to understand how different programming languages work by writing code in language you are familiar with and translating it to a different one.

Code explanation tool
![explain_code](https://user-images.githubusercontent.com/13942246/190414969-dd2d625b-c0a4-4a7d-bbee-b4d05ee5fce0.gif)

Code translation tool
![translate_code](https://user-images.githubusercontent.com/13942246/190415008-3bf7829a-d474-4b9c-bce3-92742a749f6d.gif)


## Copilot limitations

Like any tool the Copilot is not perfect in anyway and has multiple limitations that requires the developer to be vary of the code it produces.

### Limited training data

As with any machine learning model the better training data you have the better results you should receive. This is visible on the Copilot as it is not able to produce code that is not in the training data. This is especially visible when using the Copilot for new APIs or new features that are not in the training data.

Currently the Copilot is trained on 1.5 billion lines of code and 1.5 million repositories. This is a lot of code but still not enough to cover all the code that is written in the world. 

Languages that currently work best with Copilot are Python, JavaScript, TypeScript, Java, Go, C++, C#, PHP.

### Suggestions, no actual logic

The code that is generated is only a suggestion, it's not a magical tool that will remove the need for coding. The suggestions hardly contain any actual business logic that is required in the project you are currently working. As such it can only give good guesses that will require the developer to include the needed logic to the code manually.

### Complex or bloated code

Being trained on public code with wide variety of people with different skill sets the code generated can be overly complex or overly bloated containing unnecessary parts that can become a nuisance to maintain in the future. 

### Broken code

Code written by the Copilot is trained by billions of lines of code and variety of versions some of which contain bugs and are no longer valid. This can result in the Copilot creating code that contains security issues or won't work in the first place. 

### Understanding the suggestions

Utilizing the Copilot in development won't take away the need to understand what the program has written. As in the all the examples above one thing that is needed in every case is that the developer needs to understand and test the code generated by Copilot and not blindly accept the suggestions.

## Security & licensing

The release of the Copilot sparked a lot of discussion what are the legal rights of the code written with Copilot and the code that was used as training material. As the Copilot is still a new product all of these questions are still unresolved and time will tell if there needs to be changes how Copilot data and suggestions are handled.

### What happens to the code you write

The code you write with the Copilot is owned by you and you can do whatever you want with it. The Copilot does not have any rights to the code you write with it.

### Code security when using Copilot

- User Engagement Data
When you use GitHub Copilot it will collect usage information about events generated when interacting with the IDE or editor. These events include user edit actions like completions accepted and dismissed, and error and general usage data to identify metrics like latency and features engagement. This information may include personal data, such as pseudonymous identifiers.

- Code Snippets Data
Depending on your preferred telemetry settings, GitHub Copilot may also collect and retain the following, collectively referred to as “code snippets”: source code that you are editing, related files and other files open in the same IDE or editor, URLs of repositories and files paths.

### Licensing issues

The Copilot is currently licensed under the MIT license. This means that the Copilot can be used in any project and the code written with it can be used in any project. However the training data used to train Copilot can contain licensed code which is not free to use.

## Supported and upcoming features

GitHub Copilot is still a new product and as such it is constantly being developed and new features are being added.

### GitHub Copilot for companies

GitHub Copilot for companies is a new feature that allows companies to use the Copilot in their own projects. This is done by creating a private repository that is used to train the Copilot on the companies code. This allows the Copilot to learn the companies code and provide suggestions that are more relevant to the company.

## Alternative options

The GitHub Copilot is not the first AI based code suggestion tool and it won't be the last. There are multiple other tools that provide similar features to the Copilot.

### TabNine

Tabnine predicts and suggests your next lines of code based on context & syntax.
- Whole line code completions
- Full-function code completions
- Natural language to code

### Kite

One of the first tools to be released in the field of code intelligence is Kite, which was founded in 2014 to release code intelligence plugins for editors such as Atom/Vim/Spyder, initially for Python developers, but now expanded to most major development languages. The JetBrains plugin will be released in early 2020 and the VSCode plugin in early 2021.

Kite supports 16 major development languages and 16 code editors, but from my experience, it is still best at Python, which is the first language type Kite supports.

### Intellisense

IntelliSense is a code completion tool that is built into Microsoft Visual Studio. It is one of a number of similar tools that allow for intelligent code completion or intelligent text completion on different platforms.

Through the use of various algorithms, IntelliSense attempts to guess what the developer wants to type in order to complete a line of code. Using this tool may reduce typographical and syntactical errors.

Through a number of features including "list members," "parameter information" and "complete work," IntelliSense helps developers evaluate code as they are typing and use fewer keystrokes to implement certain aspects of a code. For example, "list members" will generate a list of valid members from a trigger character and limit the result according to the initial letters that have been typed in.

IntelliSense and related tools are helpful in making code writing more efficient and allow programmers to track what they have done in order to reduce errors and improve accuracy.

## Links

- **[GitHub Copilot homepage](https://github.com/features/copilot)**
- **[GitHub Copilot docs](https://docs.github.com/en/copilot)**
- **[OpenAI Codex](https://openai.com/blog/openai-codex/)**
- **[GitHub Copilot Productivity Research](https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/)**
- **[TabNine](https://www.tabnine.com/)**
- **[Kite](https://www.kite.com/)**
- **[Intellisense](https://code.visualstudio.com/docs/editor/intellisense)**
