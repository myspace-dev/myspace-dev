## Hi there 👋
<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Welcome%20to%20my%20space&fontSize=40&animation=twinkling" />
  <img src="./assets/earth_blue.gif" width="300" alt="Demo">
  <br>
  <br>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&pause=1000&width=435&lines=%E2%86%90+%E2%86%90+%E2%86%90+TECH+STACK+%E2%86%90+%E2%86%90+%E2%86%90" alt="Typing SVG" /></a>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&random=true&width=800&lines=%F0%9F%90%8D+Python+%F0%9F%A4%96+AI+%F0%9F%9B%A0%EF%B8%8F+Oracle+Siebel+CRM+;%F0%9F%9A%80+Astro%2FStarlight+%E2%9B%85%EF%B8%8F+Claudflare+;%F0%9F%8C%9F+%EF%B8%8FGit++%F0%9F%94%84++GitHub+Actions%2FCI%2FCD;%F0%9F%8C%90+HTML5+%F0%9F%8E%A8+CSS3+%E2%9A%A1+JavaScript+%F0%9F%9B%A1%EF%B8%8F+TypeScript" alt="Typing SVG" /></a>
  <br>
  <br>
  <img src="./assets/zepeto_centered.gif" width="480" alt="zepeto">
  <br>
  <br>
### `Created a custom Notepad++ syntax highlighting configuration for AstroJS.`
### `It brings clean syntax coloring and better code readability for .astro files.`
### `Notepad++ User Defined Language (UDL) for AstroJS`
👇
<details>
  <summary><kbd><strong>📋 ⌘ <mark><em> View Code </em></mark></strong></kbd></summary>
  
```xml wrap=true
<?xml version="1.0" encoding="UTF-8"?>
<NotepadPlus>
    <UserLang name="Astro" ext="astro" udlVersion="2.1">
        <Settings>
            <Global caseIgnored="no" allowFoldOfComments="yes" foldCompact="yes" forcePureLC="1" decimalSeparator="." />
            <Prefix Keywords1="no" Keywords2="no" Keywords3="no" Keywords4="no" Keywords5="no" Keywords6="no" Keywords7="no" Keywords8="yes" />
        </Settings>
        <KeywordLists>
            <Keywords name="Comments"> </Keywords>
            <Keywords name="Numbers"> </Keywords>
            <Keywords name="Operators1">= + - * / % ^ &amp; | ! &lt; &gt; ? : . , ;</Keywords>
            <Keywords name="Operators2">( ) [ ] { }</Keywords>
            <Keywords name="Folders">{ }</Keywords>
            <Keywords name="Keywords1">html head body div span a p br hr img input button form label ul ol li table tr td th thead tbody section article aside header footer nav main figure figcaption h1 h2 h3 h4 h5 h6 pre blockquote code em strong i b u small mark ins del sup sub canvas script style meta link title Fragment</Keywords>
            <Keywords name="Keywords2">id class style src href alt title type name value placeholder checked selected disabled readonly required pattern min max step autofocus autocomplete for method action enctype target rel media async defer charset lang dir hidden role viewport response time date datetime-local number range email tel url color file image submit reset button text search password onload onclick onchange oninput onsubmit onmouseover onmouseout client:load client:idle client:visible client:media client:only define:vars define:slots set:html is:inline is:global lang transition:name transition:persist transition:animate transition:animation</Keywords>
            <Keywords name="Keywords3">let const var function if else for while do switch case break continue return default import export from as new class extends super this static constructor typeof instanceof in of void delete throw try catch finally yield await async arguments true false null undefined NaN Infinity</Keywords>
            <Keywords name="Keywords4">type interface enum namespace implements extends keyof infer readonly any unknown never void</Keywords>
            <Keywords name="Keywords5">color background border margin padding font size weight family text align transform display position top right bottom left width height min-width max-width flex grid float clear list style transition animation opacity z-index box-shadow overflow visibility</Keywords>
            <Keywords name="Keywords6">true false null undefined NaN Infinity</Keywords>
            <Keywords name="Keywords7"> </Keywords>
            <Keywords name="Keywords8"> </Keywords>
        </KeywordLists>
        <Styles>
            <WordsStyle name="DEFAULT" styleID="11" fgColor="000000" bgColor="FFFFFF" fontName="" fontStyle="0" fontSize="" />
            <WordsStyle name="COMMENTS" styleID="1" fgColor="808080" bgColor="FFFFFF" fontName="" fontStyle="2" fontSize="" />
            <WordsStyle name="LINE COMMENTS" styleID="2" fgColor="008000" bgColor="FFFFFF" fontName="" fontStyle="2" fontSize="" />
            <WordsStyle name="NUMBERS" styleID="4" fgColor="FF00FF" bgColor="FFFFFF" fontName="" fontStyle="0" fontSize="" />
            <WordsStyle name="KEYWORDS1" styleID="5" fgColor="800000" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
            <WordsStyle name="KEYWORDS2" styleID="6" fgColor="0000FF" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
            <WordsStyle name="KEYWORDS3" styleID="7" fgColor="0000A0" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
            <WordsStyle name="KEYWORDS4" styleID="8" fgColor="008080" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
            <WordsStyle name="KEYWORDS5" styleID="9" fgColor="800080" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
            <WordsStyle name="KEYWORDS6" styleID="10" fgColor="000080" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
            <WordsStyle name="OPERATORS" styleID="12" fgColor="000000" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
            <WordsStyle name="DELIMITERS1" styleID="14" fgColor="A31515" bgColor="FFFFFF" fontName="" fontStyle="0" fontSize="" />
            <WordsStyle name="DELIMITERS2" styleID="15" fgColor="A31515" bgColor="FFFFFF" fontName="" fontStyle="0" fontSize="" />
            <WordsStyle name="DELIMITERS3" styleID="16" fgColor="A31515" bgColor="FFFFFF" fontName="" fontStyle="0" fontSize="" />
            <WordsStyle name="DELIMITERS4" styleID="17" fgColor="0056B3" bgColor="FFFFFF" fontName="" fontStyle="1" fontSize="" />
        </Styles>
        <Delimiters>
            <Delimiter name="STRING1" open="&quot;" close="&quot;" escape="\" />
            <Delimiter name="STRING2" open="'" close="'" escape="\" />
            <Delimiter name="STRING3" open="`" close="`" escape="\" />
            <Delimiter name="COMMENTLINE" open="//" close="" consecutive="yes" />
            <Delimiter name="COMMENT1" open="/*" close="*/" />
            <Delimiter name="COMMENT2" open="&lt;!--" close="--&gt;" />
            <Delimiter name="COMMENT3" open="---" close="---" />
        </Delimiters>
    </UserLang>
</NotepadPlus>
```

</details> 
  <br>
  <br>
  <br>
  <br>
  <br>
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&lines=Made+with+%E2%9D%A4%EF%B8%8F+%26+%E2%98%95" alt="Typing SVG" /></a>

<!--
**myspace-dev/myspace-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Here are some ideas to get you started:
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
