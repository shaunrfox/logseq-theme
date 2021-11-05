<h1 align="center">
  <br>logseq-bonofix-theme<br>
</h1>

<p align="center">
  <a href="#screenshots">🌠 Screenshots</a>
   | 
  <a href="#install">📦 Install</a>
   | 
  <a href="#whats-improved">✨ What's improved</a>
   | 
  <a href="#how-to-build">🔨 How to build</a>
</p>


This is a clean theme for [Logseq](https://github.com/logseq/logseq), focusing on bullet journal and long time writing experience. Sometimes it fixes some UI bugs for Logseq.

## Screenshots

The style is strongly inspired by [logseq-bujo-theme](https://github.com/PiotrSss/logseq-bujo-theme ) and [Notion](https://notion.so). The code is mainly based on bujo theme, and you may find the style really notion-like.

![Desktop](./media/Desktop-2021-08-09.png)

![Mobile](./media/Mobile.png)

## Install

Here are two ways of installing theme in Logseq.

### Install custome.css:

- General installation

  Copy the whole content of [custom.css](https://raw.githubusercontent.com/Sansui233/logseq-bonofix-theme/master/custom.css) into your logseq/custom.css file.

- If you are always working online

  Copy this one-line-installation into your logseq/custom.css file

  ```css
  @import url('https://cdn.jsdelivr.net/gh/sansui233/logseq-bonofix-theme/custom.css')
  ```
### (Dev Mode) Install plugin

<img src="./media/plugin.png" alt="Tags" width="450px" />

- Download the [plugin release](https://github.com/Sansui233/logseq-bonofix-theme/releases) and unpack it into a directory

- Open Logseq→Settings, enable developer mode

- Open Logseq→Plugins, load unpacked plugin

- Open Logseq→Themes, choose your theme

  > DON'T MOVE THE PLUGININ DIRECTORY ON YOUR DISK

## What's improved

**Functional style**

- **Better typography for headings and blocks**, ~~see 👉 [design details](https://github.com/Sansui233/logseq-bonofix-theme/blob/master/docs/better-typography.md)~~(The doc is for the legacy version of logseq)

- Make tippy window like responsive card instead of filling the screen and obscuring text

- Mobile: fixed-height bottom search panel

- Mobile: More stable scrolling experience

**Additional Styles**

- Add calender emoji before journal title  
  <img src="./media/journal-title-emoji.png" alt="Journal Title Emoji" width="600px" />

- Style tags as labels  
  <img src="./media/tag-label.png" alt="Tags" width="300px" />

## How to build

1. Install [node](https://nodejs.org/)
2. Clone repo  
  ```shell
  git clone https://github.com/Sansui233/logseq-bonofix-theme.git && cd logseq-bonofix-theme
  ```
3. Install sass  
  ```shell
npm install
  ```
4. Run build  

  ```shell
  npm run build
  ```

## Thanks

- [Logseq](https://github.com/logseq/logseq)
- [logseq-bujo-theme](https://github.com/PiotrSss/logseq-bujo-theme) by PiotrSss
- Dark mode of [Notion](https://notion.so)
- All feedbacks from email and discord
