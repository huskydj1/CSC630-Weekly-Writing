# Welcoming Open-Source Libraries

##### Community is an important aspect of open-source. Welcoming spaces encourage contributors and collaborators to develop and improve your work. They also motivate feedback and suggestions from new users, prompting new developments and improvements of the code base. This all starts by making your own open-source library inviting and inclusive.

## README
The exact components of a software library's README heavily depends on the library's function and design. However, there are some suggestions that will help most open-source libraries become more appealing and inviting.

### Name
Catchy, easily understandable names elevate open-source libraries, as they allow newcomers to get a broad idea of the repositories immediately upon seeing them show up from a search. If a name becomes too technical or niche, it becomes too difficult for people outside of the inner community/group to grasp the library's purpose. If one becomes to bland and broad, newcomers will have little incentive to navigate to and read through the library. Your repository's name should be catchy, concise, and self-explanatory.

### Description/Examples
Some form of media effectively demonstrating your library's function helps interested newcomers use and contribute to your code. There are a number of ways maintainers can effectively do this. The most common way is to use textual explanations/descriptions, sprinkling in links to background information. Maintainers also frequently add bulleted lists with the project's features. Comparisons between the library and similar alternatives are also helpful in giving the user an understanding of your library's specific use case and purpose.

Graphics are also very helpful in this section. Short gifs demonstrating the features in action or images of a person using the library allows readers to get a stronger grasp on the repositories' contents. [Markdownify](https://github.com/amitmerchant1990/electron-markdownify#readme) is an excellent example of a repository that uses text and graphics to describe the library. There are a number of links to specific information people might want. There is also a big graphic of someone using Markdownify to edit their markdown file.

### Installation
Listing specific steps for novices to install and use your code creates a welcoming space for users of all skill/experience levels. An off-putting aspect of using software from Github is often the act of installing and setting up the program. Removing ambiguity by walking the user through the process, especially with regards to particular language versions, operating systems, or dependencies, greatly improves your library and it's inclusiveness.

### Support/Contact
There are a number ways to offer support and help to users. One common way is to include a Frequently Asked Questions section. The exact contents should differ by project, but it is important to consider what a new user might experience. One way you might learn about such a person's struggles is to ask friends to try out your library just from the Github link. Noting their struggles, appreciations, and general feedback will give you a good idea of the kind of questions users may have. You may then improve upon this set of FAQS by adding a survey or form for interested users.

It is also helpful to give users a way to contact you for technical support or general feedback. Open-source is about growth and progress; this isn't possible if users are faced with a stonewall when facing a problem. [Markdownify](https://github.com/amitmerchant1990/electron-markdownify#readme), for examples, includes an email for any user's feedback.

[Choo](https://github.com/choojs/choo) implements these techniques very well by adding links at the very top of their README to the project's website, handbook, resources, contributing guidelines, Reddit, and chat. They have created multiple tools to support novices with documentation and guides/tutorials. They have also created a space for the community to interact and help each other. In this way, the maintainers have created a sense of community and inclusiveness for all users and contributors of their repository.

One interesting thing to note about Choo is that they created separate Github repositories for their guide/tutorials and for their documentation. This is frequently done when there is too much content to simply fit into a single README. Other avenues of more documentation are creating a wiki or building a separate website. In many ways, this itself fosters an inclusive space, as it sets aside the technical, nitty-gritty information for experienced users who know what they are looking for. This also creates a cleaner user interface for users to navigate through the repository. Concision is frequently key to attract contributors and newcomers.

### Status
A short section about the repository's status is also helpful if there are specific features in progress or if development is at a halt. Not only does this allow users to understand your project's current capabilities, but this also encourages others to develop your repository. Even after you have moved on to different pursuits, someone might choose to fork your project or step in as a maintainer, allowing further development on your project even after you have run out of steam or interest. You might also include here a request for maintainers, if you require more help.

## License
In order to make a repository that is truly open-source, it must have a license allowing others to use, change, and distribute the software. Different licenses have different restrictions for what others can do with the source code, so it's important to choose the license that fits your purposes. Github's [website](http://choosealicense.com/) for choosing licenses is very helpful for newcomers.

The reason why licenses are recommended for open-source libraries is because without one, the default copyright laws states that the code cannot be reproduced, distributed, or derived from by anyone. This is clearly not the intent of or reason behind the open-source software movement.

Most users place the license text in a file called "LICENSE.md" or "LICENSE.txt". When initially creating a repository, you can automatically add a license from Github's list.

## Changelog
A changelog chronologically lists the changes that have been applied to your repository. It may be placed in blog posts, a "CHANGELOG.md" file, or a section in the project's websites. It is essentially a summary of the past changes made to the project that make it easier for users and developers to understand the project's progression. It also gives the reader a greater view of the project, helping them understand where the repository began and how it has changed over time.

Changelogs can be created through a simple way, using git bash, and a harder way, using more sophisticated tools. For both of these methods, it is helpful if the commits you have made are of good quality. Useful and well-stated commit messages can directly be added to the changelog.

- **Simple** The ``git log`` command allows users to view the commit history of a repository. By adding a few extra characters, the command ``git log --pretty="%s"`` allows users to print the list of commits with the style that they want. ``"%s"`` itself stands for the commit title; by adding characters to the beginning, you can create a list: (``"" - %s"``). To redirect this text to a file, you can type the command ``git log --pretty="- %s" > CHANGELOG.md`` in your terminal.

- **Sophisticated** The following instructions will use the ["generate-changelog"](https://github.com/lob/generate-changelog) tool, as it is great for beginners, but others are also available. [A StackOverflow thread](https://stackoverflow.com/questions/3523534/good-ways-to-manage-a-changelog-using-git) has other plugins and packages that developers use.

  Upon [installing npm](https://www.npmjs.com/get-npm), you can use the command ``npm install generate-changelog -g`` to install the tool using your terminal.

  For this particular package, your commit messages should be in the format  ``type(category): description [flags]``. The meaning of each keyword is described in the [usage section of the package repository](https://github.com/lob/generate-changelog). To summarize it, "type" specifies the type of the commit, "flag" is optional and  marks "breaking" changes, and "category" can be another label of the user's choice.

  If your git log follows the format, you can simply navigate to the repository on your computer and type ``changelog generate`` to create a simple, elegant-looking "CHANGELOG.md" in markdown.

## Contributing
Contributing guidelines tell users how the repository maintainers would like contributions to be. Developers sometimes choose to put their contributing guidelines in a separate file named "CONTRIBUTING.md". On Github, this file will be linked when users open a pull request or an issue. According to [Github Docs](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/setting-guidelines-for-repository-contributors), the file may specify the process for creating "good" issues or pull requests; include links to external resources, such as documentation or code of conduct; and outline the "community and behavioral expectations". In this vein, maintainers may also choose to create an [issue template](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/manually-creating-a-single-issue-template-for-your-repository) and/or a [pull request template](https://help.github.com/articles/creating-a-pull-request-template-for-your-repository/) to give contributors a greater idea of the structure and specifications of a good issue or pull request.

[DVC](https://github.com/iterative/dvc#readme) has an excellent [contributing guide](https://dvc.org/doc/user-guide/contributing/core) on their website. In it, they tell the user how to contribute documentation, report a problem, submit changes, write/run tests, test remotes, and format code and commit messages. It is clearly organized with succinct, well-written descriptions and simple example text. Though it comprehensively outlines guidelines for many different types of contributions, it maintains concision and structure, making it inviting and easy to read.

Changelogs can make repositories more helpful and inviting as they clearly project the requirements of a contribution. By clearly laying out the expectations, maintainers create a productive environment for developing the source code. A changelog makes the lives of users easier, as they can adhere to a format that ensures their modifications will be helpful, and makes the lives of maintainers easier, as they can efficiently sift through contributions, understand the changes, and adopt the well-written, useful ones.

##### There is a no limit on what maintainers can do to make their repositories inviting and inclusive. The suggestions listed here were just some of the elements of popular, well-made repositories, but they are in no way the only possibile avenues. As long as you can incorporate the themes of organization, concision, and description, don't be afraid to be creative and try out new things!

### Resources
- https://github.com/matiassingers/awesome-readme
- https://www.makeareadme.com/
- https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/licensing-a-repository
- https://www.freecodecamp.org/news/a-beginners-guide-to-git-what-is-a-changelog-and-how-to-generate-it/
- https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/setting-guidelines-for-repository-contributors
- https://blog.bitsrc.io/how-to-write-beautiful-and-meaningful-readme-md-for-your-next-project-897045e3f991
- https://github.com/iterative/dvc#readme
