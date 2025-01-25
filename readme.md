# Description
Tool to convert Unix timestamp to human-readable format.

# Why?
I need a tool which:
- Converts Unix timestamp to human-readable format
- Can be accessible over the web to link it with my Alfred shortcuts.

This can be handy for people who work with Unix timestamps and love to use Alfred (thanks Ace for the recommendation 💘).

# How to Run
Open index.html in your browser.

or

Build and run the Docker image:

```bash
docker build -t unixtimestamp .
docker run -d -p 80:80 unixtimestamp
```
