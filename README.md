# VSCodeSnippets
Handy Dandy VSCode Snippets

## Setup

### Option 1
Copy snippets to global snippets folder
``` sh
git clone https://github.com/phillsv87/VSCodeSnippets.git
cd VSCodeSnippets
cp *.code-snippets ~/Library/Application\ Support/Code/User/snippets/
cd ..
rm -rf VSCodeSnippets
```

### Option 2
Clone repo to global snippets folder
``` sh
git clone https://github.com/phillsv87/VSCodeSnippets.git
cd VSCodeSnippets
cp -r * ~/Library/Application\ Support/Code/User/snippets/
cp -r ./.git ~/Library/Application\ Support/Code/User/snippets/
cd ..
rm -rf VSCodeSnippets
```