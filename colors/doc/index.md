# LIT component in doc

```js preview-story
import { html, css, LitElement } from 'lit';

class DemoRed extends LitElement {
  static get styles() {
    return css`
      :host {
        display: block;
        width: 50px;
        height: 50px;
        background-color: red;
      }
    `;
  }
}
customElements.define('demo-red', DemoRed);

export const usageInCE = () => html`<demo-red></demo-red>`;
```
