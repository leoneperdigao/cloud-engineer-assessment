# 1 - Hello, CDK

In this question, we want you to write some AWS CDK code. We want you to build a simple CRUD application to manage books. Roughly, the model can be like that:

```json
{
   "name": "<name of the book>",
   "isbn": "<universal identifier of the book>",
   "authors": "<authors of the book>",
   "languages": "<languages the book is available>",
   "countries": "<countries where the book is available>",
   "numberOfPages": "<number of pages of the book>",
   "releaseDate": "<release date of the book>",
}
```

## Requirements

* The client (the entity making the requests) MUST be able to: add one or more items, remove an item for a table, and query the items still remaining for a table.
* The application MUST, upon update request, store the item with all updated fields, except `isbn`.
* The application MUST, upon creation request, store the item with all the fields.
* The application MUST, upon deletion request, remove a specified item for a specified `isbn`.
* The application MUST, upon query request, show all items for a specified filter.
* The application MUST accept at least 10 simultaneous incoming add/remove/query requests.

Some key points to take in mind when doing this:

Do all use cases need to be handled (in the same way) by the admin or the end-user.
- Which data should (not) be shared
- How are exceptions handled & mapped
- Consistency in the specifications
- Backward compatibility

## Note

* You can use any language you feel more comfortable with, but we have a preference for `Typescript` for the CDK part and `Python` for any runtime routine.


