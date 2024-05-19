# Music-Diary-
Inspiration
Many of us find solace in sad music during tough times. Research indicates that 10% of Americans grapple with depression, and the limited medical system can't reach everyone. Music, a potent healing force, is even recognized in the medical field through music therapy. To aid those struggling with depression, we crafted MusicDiary, combining consolatory messages and music powered by AI to offer comfort.

What it does
MusicDiary interprets the emotions from users' daily diary entries, offering consolation in times of sadness and sharing in their happiness. It crafts a unique piece of music, complete with consoling lyrics derived from the diary entry, providing an unparalleled musical experience that is truly singular in the world.

The diary feature is enhanced by a calendar page, motivating users to track their emotional journey visually and audibly, with entries showcased not just in text but also through music.

Our music features include a player and a collection page, where users can listen to and view lyrics of specific tracks and discover recommended and favored songs.

A community page allows users to share healing songs, spreading comfort through both text and music.

How it's built
Utilizing Figma for design and React for development, our backend leverages Node.js. We employed Google's language analysis for emotional assessment, OpenAI for generating healing messages and lyrics, and SunoAI with a web bot for music creation. These components were integrated to form a seamless frontend-backend connection, culminating in deployment.

Challenges
The absence of a SunoAI API led us to innovate with a web bot for direct music generation on the SunoAI site, using user-provided inputs.

Accomplishments that we're proud of
We bypassed the lack of SunoAI's API by creating a web bot, aspiring to aid those with depression and contribute to a better world.

What's next for MusicDiary
Expanding MusicDiary, we envision incorporating Speech to Text for easier diary entries and partnering with medical professionals to monitor patient progress through our app, enhancing both user experience and therapeutic outcomes.

Built With
express.js
mongodb
node.js
openaiapi
react.js
sunoai
