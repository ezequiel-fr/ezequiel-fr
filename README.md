# Ezequiel Dev <br /><span style="font-size: 1rem">alias TheRedMine TheRedMaths</span>

```ts
class Ezequiel extends Dev {

    private skills: Array<string> = [];

    private portfolioURL: string = "https://theredminetheredmine.github.io/temp-portfolio";


    constructor() {
        super();
        this.getSkills();
    }


    private getSkills(): void {
        [
            'developper',
            'software engineer',
            'translater',
        ].forEach(a => this.skills.push(a));
    }


    /**
     * Get my URL Portfolio
     * @returns {string}
     */

    public getPortfolio = (): string => this.portfolioURL;

}

export default Ezequiel;
```

My Portfolio → [here](https://theredminetheredmine.github.io/tmp_portfolio)
