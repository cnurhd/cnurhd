---
title: Style Guide
subtitle: 이 사이트에 작성된 문서의 스타일입니다. 참고하시면 도움이 됩니다.
image: images/5.jpg
seo:
  title: Theme Style Guide
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Theme Style Guide
      keyName: property
    - name: 'og:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
      keyName: property
    - name: 'og:image'
      value: images/5.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Theme Style Guide
    - name: 'twitter:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
    - name: 'twitter:image'
      value: images/5.jpg
      relativeUrl: true
template: page
---
**This is paragraph. 작성된 문단이 이렇게 보입니다.**

이 사이트의 문서는 기본적으로 markdown으로 작성되었고, image는 되도록 SVG file을 사용하며, table은 markdown 또는 HTML을 이용하여 작성하였습니다.

# This is an H1

## This is an H2

### This is an H3

#### This is an H4

## Quoting

인용문은 다음과 같이 삽입됩니다.

> Creativity is allowing yourself to make mistakes. Design is knowing which ones to keep. - Scott Adams

<hr />

## Unordered Lists (번호가 없는 목록)

*   Donec non tortor in arcu mollis feugiat
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit
*   Donec id eros eget quam aliquam gravida
*   Vivamus convallis urna id felis
*   Nulla porta tempus sapien

## Ordered Lists (번호가 있는 목록)

1.  Donec non tortor in arcu mollis feugiat
2.  Lorem ipsum dolor sit amet, consectetuer adipiscing elit
3.  Donec id eros eget quam aliquam gravida
4.  Vivamus convallis urna id felis
5.  Nulla porta tempus sapien

## Video Embeds

<iframe width="560" height="315" src="https://www.youtube.com/embed/8uuFIi-ghPI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Code Blocks

Blocks of code are either fenced by `lines with three back-ticks`, or are indented with four spaces.

    <!-- Some example CSS code -->
    body {
      color:red;
    }

```javascript
window.$docsify = {
  coverpage: true,

  // Custom file name
  coverpage: 'cover.md',

  // mutiple covers
  coverpage: ['/', '/zh-cn/'],

  // mutiple covers and custom file name
  coverpage: {
    '/': 'cover.md',
    '/zh-cn/': 'cover.md'
  }
};
```

## Tables

<div class="responsive-table">
  <table>
      <caption>Table with thead, tfoot, and tbody</caption>
    <thead>
      <tr>
        <th>Header content 1</th>
        <th>Header content 2</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Body content 1</td>
        <td>Body content 2</td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <td>Footer content 1</td>
        <td>Footer content 2</td>
      </tr>
    </tfoot>
  </table>
</div>

<div class="note"><strong>Note:</strong> Both of the features you used above are parts of the Document Object Model (DOM) API, which allows you to manipulate documents.</div>

<div class="important"><strong>Important:</strong> In this article, try entering the example code lines into your JavaScript console to see what happens. For more details on JavaScript consoles, see Discover browser developer tools.</div>

<div class="comment"><strong>Comment:</strong> In this article, the author's comment are inserted and the blue box is outlined around the paragraph.</div>
