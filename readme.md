# Main features of astro:

    Astro is a component based technologie for develop static web applications and websites, giving a architecture for work with components, and the best feature of <strong>Astro components</strong> are the <strong>Astro islands</strong> that are isolated UI interactive componentes inside HTML page.

## Versatility of Astro:

    Astro have the feature of let us integrate several JS web frameworks for take avantage of the astro features and benefits:

## Astro IDE:

    In my case i'm using ubuntu, but you could need install node js and Astro's dependecie for start development.

## Performance and speed benefits:

    Astro offers somethin called SSG (Static sites generation), this allow a fastest rendering because our sites will be static using other features that allow us render only the neccesary components.

## Partial Hydratation:

    Astro only will render (Hydratate) the interactive parts of our page for a better speed and performance.

## State Management: 

    You can share state between islands using tools like Nano Stores, allowing for communication between different framework components.


# Struture of Astro:

    Astro have the <strong>public</strong> dir for let all our elements non releated with the code of project, there're the pieces of multimedia as mp3, mp4, pdf and others for our pages.

    Then we have <strong>src</strong> and the config files like gitignore, package.json, package.json., that will be for modify our dev enviroment and developt our project

    If we want to use the astro feature of work with diferent JS frameworks or use CSS libraries or supersets we can use as modules in our <strong>astro.config.mjs</strong>


# Deploy of Astro projets

    For make proves with the source files we have to set our local <strong>Vite</strong> server for prove our base app:

    We've write:
    <strong>npm run dev</strong>

    And for <strong>deploy</strong> our app we have to run a command that'll create a <strong>dist</strong> dir that will a <strong>index.html</strong> with our multimedia and functional page, this file is that one we can upload and deploy in a hosting

    we've to write:
    <strong>npm run build</strong>

    And for get a preview of our project we write:
    <strong>npm run preview</strong>

    This last commands render all our content in <strong>dist</strong> dir


# Astro syntax:

    This syntax is a super set of HTML with the feature of write JS server side code like this:

        ---
    const title = "Hello, Astro!";
        ---

    <h1>{title}</h1>
    <p>This is an Astro component.</p>
