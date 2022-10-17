Instruktioner:

1) Ni ska efterlikna det som visas i videon. Ni skapar er egen HTML- och CSS
2) Det finns en breakpoint på 500px
3) Vid breakpointen blir navigationen en kolumn och författarnamnet dyker upp
4) Vid breakpointen dyker ett meddelande upp (mellan navigation och innehåll)

Tips:
- Använd <span> för att markera upp författarnamnet (ett inline-element) för att visa/dölja
- Ytan mellan länkarna kan lämpligtvis lösas med "gap"
- Bilderna i navigationen är placerade som bakgrundsbilder i CSS
- Texten i länkarna använder sig av "text-shadow" så kontrasten blir bättre mot bakgrundsbilderna

Elementet <span> används för att markera upp någonting i löpande text, för att sedan style:a det. T.ex.

<p>This is <span class="red">some red text</span></p>
.red { color: red; }

Meddelande:
    Attention! You're watching the webpage on a screen that is smaller than 500px.
Innehåll:
    A museum (/mjuːˈziːəm/ mew-ZEE-əm; plural musea or museums) is an
    institution that cares for (conserves) a collection of artifacts and other
    objects of artistic, cultural, historical, or scientific importance. Many
    public museums make these items available for public viewing through
    exhibits that may be permanent or temporary