# learning-tailwind-framework
Learning tailwind css one class at a time

**Tailwind setup**

[Help Guide](https://tailwindcss.com/docs/guides/create-react-app)

**Install Tailwind CSS**

1. Install tailwindcss and its peer dependencies via npm, and then run the init  command to generate both tailwind.config.js and postcss.config.js.

        npm install -D tailwindcss
        npx tailwindcss init

**Configure your template paths**

2. Add the paths to all of your template files in your tailwind.config.js file.

        module.exports = {
            content: ["./src/**/*.{html,js}"],
            theme: {
            extend: {},
            },
            plugins: [],
        }

**Add the Tailwind directives to your CSS**

3. Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

        @tailwind base;
        @tailwind components;
        @tailwind utilities;

        Start your build process
        Run your build process with npm run start.
        npm run start

**Start using Tailwind in your project**

4. Start using Tailwind’s utility classes to style your content.

        export default function App() {
        return (
                <h1 className="text-3xl font-bold underline">
                Hello world!
                </h1>
            )
        }


