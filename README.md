# Title

## Title

### Title

#### Title

##### Title

###### Title

Title

- bullet point

https://www.google.fr

[mon lien](https://www.google.fr)

| header1 | header2 |
| ------- | ------- |
| value1  | value2  |

![mon image](https://www.parcanimalierlabarben.com/wp-content/uploads/2023/07/fiche_loutre_carre.jpg)

> citation

petit exemple `de code` intégré

```js
@afterCreate()
  static async createToken(user: User) {
    const token = await Token.create(
      {
        id: randomUUID(),
        type: TokenType.activation,
      },
      { client: user.$trx }
    )

    await token.related('user').associate(user)
  }
```
