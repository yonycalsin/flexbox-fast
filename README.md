## Flexbox Fast

### Installation

```bash
# For npm
npm install flexbox-fast

# For yarn
yarn add flexbox-fast
```

### Usage

```scss
.fx {
   display: flex;

   // Direction
   &-dr,
   &-rw,
   &-rnw {
      flex-direction: row;
   }

   &-dc,
   &-cw,
   &-cnw {
      flex-direction: column;
   }

   // Wrap
   &-ww,
   &-rw,
   &-cw {
      flex-wrap: wrap;
   }

   &-wnw,
   &-rnw,
   &-cnw {
      flex-wrap: nowrap;
   }

   // Justify Content
   &-jcc,
   &-cc {
      justify-content: center;
   }

   &-jcfs {
      justify-content: flex-start;
   }

   &-jcfe {
      justify-content: flex-end;
   }

   &-jcsb {
      justify-content: space-between;
   }

   &-jcsa {
      justify-content: space-around;
   }

   // Align Items
   &-aic,
   &-cc {
      align-items: center;
   }

   &-aifs {
      align-items: flex-start;
   }

   &-aife {
      align-items: flex-end;
   }

   &-ais {
      align-items: stretch;
   }
}
```
