---
sidebar_position: 1
---

# Introduction

**SAP ABAP** is a business purpose programming Language. Well that's what everyone says. but what exactly is this business purpose mean?

**Let me explan**

Normally whern we are using any general purpose programming language like **python** or **java** we can do almostly anything using it considering that we have a proper runtime available in our system for it.

But **ABAP** was especially desined for business data that basically means we won't be dealing with all the complex features as provided by any other general programming language.

In the real world scenario we basically deal with below types of development objects

-**R** Reports

-**I** Interfaces

-**C** Conversions

-**E** Enhacements

-**F** Forms

-**W** Workflow

## Reports
For any sucessful business, it becomes very to get a tunnel vision of realtime data at any point of time. SAP has provided Reports Object for these purposes. There are different kind of report for example list, ALV, Module Pool but in short we can say that Reports are as simple as a way to view some data. It gives a summary of data mostly in tabular format.
We basically get the data from table and show it to the user. These kind of objects are quite simple( perfect for a new ABAP developers to explore ) as it mostly deals with fectching the data from user based on some values. In our case the term is known as **selection screen** and do some calculation if required and show it to the user.

## Interfaces
It is a way in which the mordern computers communicate with each others. SAP provided various technologies like RFC, IDOC, BAPIs etc to communication with other systems. 

## Conversions
Consider you want to store some data in your system. Would it make sense to do a repetative task again and again? No right?
For this reason SAP provides various data loading and conversion mechanisms which can be used to upload the data in a proper way and in a proper format in the SAP systems

## Forms
When you visit a store and buy something, you might have recived a reciept from the store which is basically a proof mechanism to know that you are the actual buyer from that store. This becomes an intregal part for a business to have a all these documents created in a proper way and with proper calculation. SAP provides various technologies like SAP Script( obsolute ), SmartForms and Adobe Forms for the same purpose.

## Workflow
Business always works in an heirarchy and there heirarchy need a proper way of approval and rejection mechanism. SAP provides Workflow technologies to automate this flow. Once it is setup using proper roles the process becomes very smooth.

:::note

In most of the cases you might see that **W** of RICEFW is missing. This is no coincidence, as it is mostly configuration but sometimes we might get into a situation where actual ABAP development have to be done.

:::

Add **Markdown or React** files to `src/pages` to create a **standalone page**:

- `src/pages/index.js` → `localhost:3000/`
- `src/pages/foo.md` → `localhost:3000/foo`
- `src/pages/foo/bar.js` → `localhost:3000/foo/bar`

## Create your first React Page

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at [http://localhost:3000/my-react-page](http://localhost:3000/my-react-page).

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).
