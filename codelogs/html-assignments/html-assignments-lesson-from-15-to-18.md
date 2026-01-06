## Solve [3] assignments related to [Table, Div]

### Assignments 1

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Table, Div</title>
  </head>
  <body>
    <table width="100%" border="1">
      <caption>
        Members Data
      </caption>
      <thead>
        <tr>
          <th scope="col">Group</th>
          <th scope="col">Avatar</th>
          <th scope="col">Name</th>
          <th scope="col">Email</th>
          <th scope="col">Character</th>
          <th scope="col">Profile</th>
        </tr>
      </thead>
      <tbody align="left">
        <tr>
          <th scope="row" rowspan="2">Ninja</th>
          <td><img src="https://placehold.co/40x40/ff0000/FFFFFF/webp" alt="avatar" /></td>
          <td>
            Osama <br />
            Mohamed
          </td>
          <td>
            o1@nn.sa <br />
            <hr />
            o2@nn.sa
          </td>
          <td>&copy;</td>
          <td><a href="#">Profile</a></td>
        </tr>
        <tr>
          <td><img src="https://placehold.co/40x40/0000ff/FFFFFF/webp" alt="avatar" /></td>
          <td>
            Shady <br />
            Nabil
          </td>
          <td>s@nn.sa</td>
          <td>&trade;</td>
          <td><a href="#">Profile</a></td>
        </tr>
        <tr>
          <th scope="row">Monsters</th>
          <td><img src="https://placehold.co/40x40/000000/FFFFFF/webp" alt="avatar" /></td>
          <td>
            Mohamed <br />
            Ibrahim
          </td>
          <td>m@nn.sa</td>
          <td>&REG;</td>
          <td><a href="#">Profile</a></td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <th scope="row" colspan="5" align="left">Total Members</th>
          <td>3</td>
        </tr>
      </tfoot>
    </table>
  </body>
</html>
```

### Assignments 2

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Table, Div</title>
  </head>
  <body>
    <table border="1" cellspacing="0" cellpadding="20">
      <caption>
        Members Points
      </caption>
      <thead>
        <tr>
          <th scope="col">Date</th>
          <th scope="col">Name</th>
          <th scope="col">Points</th>
        </tr>
      </thead>
      <tbody align="center">
        <tr>
          <th scope="row" rowspan="4">Month</th>
          <td>Osama Mohamed</td>
          <td>100</td>
        </tr>
        <tr>
          <td>Sayed Mohamed</td>
          <td>100</td>
        </tr>
        <tr>
          <td>Ahmed Mohamed</td>
          <td>100</td>
        </tr>
        <tr>
          <td>Eman Mohamed</td>
          <td>100</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```

### Assignments 3

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Table, Div</title>
  </head>
  <body>
    <table border="1" cellspacing="3" cellpadding="10">
      <caption>
        Complex Table
      </caption>
      <thead>
        <tr>
          <th scope="col">Year</th>
          <th scope="col">Group</th>
          <th scope="col">Language</th>
          <th scope="col">Done</th>
          <th scope="col">Passed</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row" rowspan="5">2022</th>
          <th rowspan="2">Elzero</th>
          <td>HTML</td>
          <td colspan="2">Yes</td>
        </tr>
        <tr>
          <td>CSS</td>
          <td colspan="2">Yes</td>
        </tr>
        <tr>
          <th rowspan="3">Heroes</th>
          <td>JS</td>
          <td>Yes</td>
          <td>No</td>
        </tr>
        <tr>
          <td>PHP</td>
          <td colspan="2">Yes</td>
        </tr>
        <tr>
          <td>Python</td>
          <td>No</td>
          <td>No</td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```
