# ezequiel-fr <span style="font-size: 1rem">(alias Ezequiel Dev)</span>

<hr>

```ts
class Ezequiel extends Dev {
    private skills: string[] = [];
    private portoflio: string = "https://ezequiel-fr.github.io/";

    constructor() {
        super();
        this.skills();
    }

    protected get skills(): void {
        [
            ...this.skills,
            'developper',
            'software engineer',
            'translater',
        ].forEach(e => this.skills.push(e));
    }

    /**
     * Get my URL Portfolio
     * @returns {string}
     */
    public get portfolio = (): string => this.portfolio;
}

export default Ezequiel;
```
<br>

![Ezequiel's GitHub stats](https://github-readme-stats.vercel.app/api?username=ezequiel-fr&show_icons=true&bg_color=30,467,469&title_color=fff&text_color=ddd&hide_border=true&border_radius=10)

<br>

My Portfolio → [here](https://ezequiel-fr.fr/)

<hr>

![visits](https://profile-counter.glitch.me/%7Bezequiel-fr%7D/count.svg)
