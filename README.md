# chats-at-st-matts frontend

## About Chats at St Matt's
A blog/forum for young people in Plymouth to ask questions and share their meditations on God, the Bible, and life.

## Technology and deployment
As planned on 01/10/2022
- Next.js with Typescript as frontend
- Node.js with Typescript as backend
- PostgreSQL database in Render (but may be vulnerable to scaling up challenges)
- 

## MVP objectives
- Step 1: basic blog
  - Blog post page, where the dev submits a post
  - Homepage, with links to multiple blog post pages
  - Design using bright colours
- Step 2: forum functionality
  - Question pages, with a discussion point at the top, available
  - Users can give responses to questions, with a character range for comments (not too small or too long)
  - Users can submit their own questions, no approval process used at this point
  - Authentication for users to avoid spam posters and so they don't have to enter their details each time
  - Authorization permission levels of 'admin' and 'standard' for now - to separate who can make the official blog posts from those who are only supposed to use the forum functionality

## Fututre goals
- Step 3: media and activity platform
  - Embed podcast videos and audio
  - Add specific functionality for small groups, starting with Dartmoor Adventures hiking group
  - Migrate database to a non-relational database format to cope with project changes?
- Step 4+: established site
  - Patreon or similar financial support (required if databases become too full or speed increase required)
  - Authorization permissions for accounts expanded based on biblical gifts (subject to change)
    - Craftsmanship (for developers, but needs the other permissions to change site content)
    - Teaching (can make blog posts)
    - Shepherding (can regulate question threads)
    - Saintly (able to access some Christian-only information and tools)
    - Worldly (no special permissions)
  - Use React Native to make a dedicated mobile app version
