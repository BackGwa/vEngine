
### **AI Prompt**

---

**🙂 Person**<br>
I'm trying to build a new web-based game engine.<br>
Please create a folder name to collect source code or resources.<br><br>

**🖥️ chatGPT 3.5**<br>
Sure, here are some suggestions:

1. For the folder containing the source code of the game, you can use a name like "src" which is short for "source". This is a common convention in software development, and it's easy to remember.

1. For the folder collecting the resources of the game, you can use a name like "assets" or "resources". Both of these names are commonly used in game development to refer to the files that contain game data such as graphics, audio, and other media.

So, to summarize:

1. Source code folder: "src"
1. Resources folder: "assets" or "resources"


Of course, you can choose any name you like for these folders as long as they are descriptive and easy to remember.

<br>

---

<br>

**🙂 Person**<br>
I see, so do I use the customary 'src' and 'assets'?<br><br>

**🖥️ chatGPT 3.5**<br>
Yes, "src" and "assets" are common and widely used names for the folders that contain source code and game assets, respectively. Using these names can make your code and resources more easily understood by other developers who may be familiar with the convention.

However, you can choose any name that makes sense to you and your team. The most important thing is to use a descriptive and meaningful name that clearly communicates the contents of the folder. This can help you and other developers find and manage the files more easily as your project grows in size and complexity.

<br>

---

<br>

**🙂 Person Work**<br>
Create 'src' and 'assets' folders

<br>

---

<br>

**🙂 Person**<br>
The game engine I want to make is a visual novel type game engine like 'renpy'. Based on this, please subdivide the folder so that various resources can be contained in the 'assets' folder.<br><br>

**🖥️ chatGPT 3.5**<br>
Sure, here are some suggestions for subfolders within the "assets" folder that could be used to organize resources for a visual novel game engine:

1. "Backgrounds": This folder can contain images of the backgrounds used in the game. These images can be used to set the scene and create the setting for the story.

1. "Characters": This folder can contain images of the characters used in the game. These images can be used to show the appearance of the characters in the game.

1. "Music": This folder can contain audio files for the music and sound effects used in the game. This can include background music, sound effects for various actions, and any other audio used in the game.

1. "Fonts": This folder can contain any custom fonts used in the game. Visual novels often make use of unique fonts to match the aesthetic of the game.

1. "Scripts": This folder can contain any scripting files used to control the game mechanics. This can include files that define the flow of the story, dialogue, and any custom game mechanics.

1. "UI": This folder can contain any images or files used to create the game's user interface. This can include buttons, menus, and other UI elements.

1. "Miscellaneous": This folder can contain any other resources that do not fit into the other categories. This can include files such as logos, splash screens, or other assets.

These are just some suggestions, and the exact folder structure will depend on the specifics of your game and the resources you use. The goal is to keep the assets organized and easy to find, so you can quickly make changes and iterate on the game.

<br>

---

<br>

**🙂 Person Work**<br>
Create 'Backgrounds', 'Characters', 'Music', 'Fonts', 'Scripts', 'UI' and 'Miscellaneous' folders in the 'assets' folder


<br>

---

<br>

**🙂 Person**<br>
I want to make it easy for people who want to develop using this engine to add a story to the game. How can I do that?<br><br>

**🖥️ chatGPT 3.5**<br>
To make it easy for people to develop stories using your game engine, you can provide a user-friendly way for them to create and edit the content. Here are a few suggestions:

1. Visual editor: A visual editor can provide a graphical interface for users to create and edit the story content. This can include features such as drag-and-drop, WYSIWYG (What You See Is What You Get) editing, and previewing the content in real-time. A visual editor can help users who may not be familiar with programming languages to create and edit the content easily.

1. Markup language: You can create a simple markup language specifically for your game engine that allows users to define the story content using plain text. This can be easier for users who are familiar with text editors and prefer to write the story content directly. The markup language should be easy to learn and understand, and you can provide documentation and examples to help users get started.

1. Scripting language: You can also provide a scripting language for users to define the story content. This can provide more flexibility and control for advanced users who are comfortable with programming languages. You can use an existing scripting language or create a custom language specifically for your game engine.

1. Templates and examples: You can provide templates and examples to help users get started with creating a story. These can include pre-defined story structures, character templates, and dialogue examples. This can make it easier for users to get started and can also help ensure consistency in the game's story and characters.

1. Integration with popular tools: You can integrate your game engine with popular tools used for creating stories and visual novels, such as Twine or InkleWriter. This can make it easier for users who are already familiar with these tools to switch to your engine.

By providing user-friendly tools and resources, you can make it easier for people to develop stories using your game engine, which can help attract more users and make your engine more successful.

<br>

---

<br>

**🙂 Person**<br>
Okay, but which one of them is easy for us to create and also makes it easier for users to write stories for the game?

**🖥️ chatGPT 3.5**<br>
The choice of method depends on the goals and constraints of your project. Here are some considerations for each option:

1. Visual editor: A visual editor can be a good choice if you want to make it easy for non-technical users to create content. However, creating a visual editor can be time-consuming and may require significant development resources.

1. Markup language: A markup language can be an efficient and flexible way to define story content. It can be relatively easy to create a simple markup language, and users can use any text editor to create and edit content. However, some users may find it difficult to learn a new markup language.

1. Scripting language: A scripting language can provide the most flexibility and control over the story content. However, creating a new scripting language can be complex and time-consuming, and it may require users to learn a new programming language.

1. Templates and examples: Providing templates and examples can be a good way to help users get started with creating content. However, it may not provide enough flexibility for more advanced users.

1. Integration with popular tools: Integrating with existing tools can be a good way to leverage existing user bases and reduce the learning curve for users. However, it may require significant development resources to create the integration.

Considering these factors, a good option might be to create a simple markup language with templates and examples. This can provide users with a straightforward way to create and edit story content, while still allowing for some flexibility and customization. You can also provide a visual editor or scripting language as optional features for more advanced users.

<br>

---

<br>

**🙂 Person**<br>
Well, just pick one that's easy for us to develop this engine.

**🖥️ chatGPT 3.5**<br>
If your main concern is ease of development for your game engine, then creating a markup language may be the easiest option.<br><br>

Creating a markup language can be relatively simple and requires fewer development resources compared to a visual editor or a custom scripting language. You can define a syntax that allows users to define the story content using plain text, and then write a parser to convert the text into a format that the game engine can understand.

To make it even easier for users, you can provide documentation and examples to help them get started with using the markup language. This can include simple templates for common elements in a visual novel, such as dialogue, character descriptions, and scene transitions.

Overall, creating a markup language can be a good balance between ease of development and ease of use for your users.

<br>

---

<br>

**🙂 Person**<br>
So what should we do with the grammar of the markup language? Please make it yourself.<br><br>

**🖥️ chatGPT 3.5**<br>
Sure, here is an example of a simple markup language grammar that could be used for a visual novel game engine:

1. Dialogue
    Syntax: `[[speaker name|dialogue text]]`
    Example: `[[John|Hello, how are you?]]`

1. Choices
    Syntax: `[choice text -> target node]`
    Example: `[Ask about the weather -> Weather]`

1. Scene transitions
    Syntax: `[[scene transition]]`
    Example: `[[fade out]]`

1. Comments
    Syntax: `# comment text`
    Example: `# This is a comment`

1. Label
    Syntax: `[[label_name:]]`
    Example: `[[start:]]`

1. Goto
    Syntax: `[[goto label_name]]`
    Example: `[[goto start]]`

In this example, the markup language includes syntax for dialogue, choices, scene transitions, comments, label, and goto statements. The dialogue syntax allows the user to specify the speaker and their dialogue text, while the choice syntax allows the user to define branching paths in the story. The scene transition syntax allows the user to specify effects when transitioning from one scene to another, and the comments syntax allows the user to add comments to the code without affecting the story.

The label and goto statements are used to define and jump to specific points in the story. This can be useful for implementing game mechanics such as checkpoints or multiple endings.

Of course, the actual syntax of the markup language will depend on the specific requirements of your game engine. But this example should give you an idea of how you can define a simple markup language that can be used to create a visual novel-style game.

<br>

---

<br>

**🙂 Person**<br>
I'm going to make an engine using JavaScript, so can I fully implement the above grammar in JavaScript?<br><br>

**🖥️ chatGPT 3.5**<br>
Yes, you can fully implement the above markup language grammar in JavaScript. 

You can use regular expressions to parse the markup language syntax and convert it into JavaScript objects that represent the story content. For example, you can use a regular expression to match the dialogue syntax and extract the speaker and dialogue text, and then create a JavaScript object that represents the dialogue.

Here's a basic example of how you could use regular expressions to parse the markup language syntax for dialogue:

```js
const DIALOGUE_REGEX = /\[\[(.*?)\|(.*?)\]\]/;

function parseDialogue(line) {
  const match = line.match(DIALOGUE_REGEX);
  if (match) {
    const speaker = match[1];
    const text = match[2];
    return { type: "dialogue", speaker, text };
  } else {
    return null;
  }
}
```

In this example, the `DIALOGUE_REGEX` regular expression matches the dialogue syntax `[[speaker name|dialogue text]]`. The `parseDialogue` function takes a line of text as input and uses the regular expression to extract the speaker and dialogue text. It then creates a JavaScript object with the type `"dialogue"` and the extracted speaker and text properties.

You can use a similar approach to parse the syntax for choices, scene transitions, comments, and other elements of the markup language. Once you've parsed the story content into JavaScript objects, you can use them to drive the behavior of your game engine.

Keep in mind that this is just a basic example, and you may need to add additional error handling and validation to handle more complex syntax and ensure that the input is well-formed.

<br>

---

<br>

**🙂 Person**<br>
What should be the file name for the code above?<br><br>

**🖥️ chatGPT 3.5**<br>
The file name for the code that parses the markup language syntax and converts it into JavaScript objects could be something like `story-parser.js` or `story-parser-util.js`, depending on your preference.

You may also want to consider creating a separate module or file for each type of story element (e.g. dialogue, choices, scene transitions) to keep the code organized and modular. In this case, you could use a naming convention like `dialogue-parser.js`, `choices-parser.js`, and so on.

Ultimately, the naming convention you choose will depend on your personal preference and the overall structure of your codebase.

<br>

---

<br>

**🙂 Person**<br>
I want to manage these codes in one file. If so, would it be correct to name the file 'story-parser.js'?<br><br>

**🖥️ chatGPT 3.5**<br>
Yes, naming the file `story-parser.js` would be a good choice if you want to manage all the code for parsing the story content in one file. 

In this case, you can define separate functions or classes within the file to handle each type of story element, such as `parseDialogue`, `parseChoices`, and `parseSceneTransitions`. You can then export these functions or classes as necessary to be used in other parts of your game engine.

Using a single file for parsing the story content can help keep your codebase organized and modular. It also makes it easier to manage dependencies and avoid conflicts between different parts of your game engine.

<br>

---

<br>

**🙂 Person Work**<br>
Create 'story-parser.js' file in src folder

<br>

---

<br>

**🙂 Person**<br>
I created a file called 'story-parser.js' inside the src folder.<br><br>

**🖥️ chatGPT 3.5**<br>
Great! Now you can start building out the functions or classes within the `story-parser.js` file to handle each type of story element.

As you develop the parser functions, be sure to test them thoroughly to ensure they are correctly parsing the input and generating the expected output. You may also want to consider adding error handling and validation to ensure that the input is well-formed and prevent any potential issues with the parsing process.

Once you have a working parser, you can integrate it into your game engine code to load and display the story content as necessary.