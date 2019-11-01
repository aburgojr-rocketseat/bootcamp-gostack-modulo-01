# Module 01 - Environment and Concepts

> First API using NodeJS

This project is a simple API using NodeJS and contains a simple User CRUD

## Table of contents

- [Development setup](#development-setup)
- [Usage example](#usage-example)
- [Meta](#meta)


## Development setup

After cloning, to run this project, install it locally using `yarn`:

```sh
yarn install
yarn dev
```

The project is running in `http://localhost:3000`


## Usage example

Test the API using Postman, Insomnia or Curl:

- Host: `http://localhost:3000`

<table>
  <thead>
    <th>Method</th>
    <th>Endpoint</th>
    <th>Body</th>
    <th>Description</th>
  </thead>
  <tbody>
    <tr>
      <td>GET</td>
      <td><i>/users</i></td>
      <td></td>
      <td>List all users</td>
    </tr>
    <tr>
      <td>POST</td>
      <td><i>/users</i></td>
      <td>
        <pre>
          {
            "name": "Jonh Doe"
          }
        </pre>
      </td>
      <td>Create a user</td>
    </tr>
    <tr>
      <td>GET</td>
      <td><i>/users/1</i></td>
      <td>
        {
          "name": "Jonh Doe Jr"
        }
      </td>
      <td>Show user</td>
    </tr>
    <tr>
      <td>PUT</td>
      <td><i>/users/1</i></td>
      <td></td>
      <td>Update user</td>
    </tr>
    <tr>
      <td>DELETE</td>
      <td><i>/users/1</i></td>
      <td></td>
      <td>Delete user</td>
    </tr>
  </tbody>
</table>


## Meta

Developed by Agnaldo Burgo Junior - agnaldoburgojr@gmail.com

Thanks to Rocketseat for the shared knowledge. You make a difference!
