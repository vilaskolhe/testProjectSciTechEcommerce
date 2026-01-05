# Page snapshot

```yaml
- generic [ref=e3]:
  - navigation [ref=e4]:
    - link "Products" [ref=e5]:
      - /url: /
    - link "Cart" [ref=e6]:
      - /url: /cart
  - generic [ref=e7]:
    - heading "Cart" [level=1] [ref=e8]
    - generic [ref=e9]:
      - generic [ref=e10]:
        - heading "Laptop" [level=2] [ref=e11]
        - paragraph [ref=e12]: "Price: $999.99"
        - paragraph [ref=e13]:
          - text: "Quantity:"
          - button "-" [ref=e14] [cursor=pointer]
          - text: "2"
          - button "+" [ref=e15] [cursor=pointer]
        - button "Remove" [ref=e16] [cursor=pointer]
      - 'heading "Total: $1999.98" [level=2] [ref=e17]'
      - link "Checkout" [ref=e18]:
        - /url: /checkout
```