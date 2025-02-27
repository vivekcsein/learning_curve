<h1>[Programming by VivekCSE] (https://vivekcse.in/) </h1>

<h3>install pnpm globally</h3>
<p>

    npm install -g pnpm

<p>

<h3>create next app </h3>
<p>

    pnpm create next-app@latest .

</P>

<h3>install "Sass" css library platform as developer dependency</h3>
<p>

    pnpm add --save-dev sass

</p>

<h3>add in next.config.js</h3>
<p>
    
    const path = require('path');</p>
    sassOptions: {
        includePaths: [path.join(__dirname, 'styles')],
    },
</p>

<h3>run development server</h3>
<p>
    
    pnpm dev
</p>
<p>

    http://localhost:3000/

</p>

<h3>create .env.local file for local environment varibales</h3>
<h3>create .env.production file for production level environment varibales</h3>
<h3>create .env.sample file for uploading on github as sample environment varibales</h3>
<p>

    .env.local
    .env.production
    .env.sample

</p>
