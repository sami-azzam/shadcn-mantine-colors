[Shadcn](https://github.com/shadcn-ui) Theme colors for Mantine UI.

# How to Use
```ts
import colors from "shadcn-mantine-colors"; //OKLCH format
import { MantineProvider, createTheme } from '@mantine/core';

const theme = createTheme({
    colors: colors
});

function App() {
  return (
      <MantineProvider theme={theme}>
        <div>page content</div>
      </MantineProvider>
  );
}
```

You can also import other formats:

```ts
import {colorsRGB, colorsHSL, colorsHEX} from "shadcn-mantine-colors";
```
