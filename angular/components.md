Basic lazy component.

```typescript
import {Component, OnInit} from '@angular/core';

@Component({
  selector: 'app-component',
  templateUrl: './app-component.component.html',
  styleUrls: ['./app-component.component.scss']
})
export class AppComponent implements OnInit {
  constructor() {}

  ngOnInit() {}
}

```
