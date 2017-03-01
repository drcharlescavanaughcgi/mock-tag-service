# mock-tag-service
A mock service that returns one or more tags in JSON given an HTTP request to the server at port 3000 using [typicode/json-server](https://github.com/typicode/json-server) URL syntax. For example, `http://localhost:3000/tags?tagName_like=Temp` returns `[
  {
    "tagId": "c3a7f165-d83e-4d69-8514-082fd5395f10",
    "tagName": "Tempus"
  },
  {
    "tagId": "2be2f4da-21d0-43dc-8c8a-9229885deec9",
    "tagName": "Tempor"
  }
]`.
All Tag data is in output.json and dummy data created using [webroo/dummy-json](https://github.com/webroo/dummy-json) and the template.hbs file.
