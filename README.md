# Personal Blogging application

## Description
This is a personal blogging application with both markdown as well as WYSIWYG editor has features of comments and comment moderation. Readers can also submit their blogs if they wish to get their blog published as well. 

## Getting Started

### Open Using Daytona

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).

2. **Create the Workspace**:
   ```bash
   daytona create https://github.com/rusted-dreams/my-blog-app
   ```

### Add Forwarded Port

In your Text Editor/IDE, add 4000 as the forwarded port.

### Start the Application

Navigate to the project root and run the following commands:

```bash
daytona use development
```

Start the server:

```bash
pnpm run dev
```

## Technologies Used:
- typescript
- tailwind
- postgres (as database)
- Nextjs
- Nextauth
- mdx - for markdown editor
- friola (wysiwyg editor)
