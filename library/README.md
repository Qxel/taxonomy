# Qxel Taxonomy

Qxel Taxonomy has changed to **single directory based**.

- Each directory is a **category**.
- Each category has files in this format:

~~~yml
n_{taxonomy}.yml
~~~

For example:

~~~yml
1_author.yml
2_book.yml
~~~

And inside it, items like famous authors.

---

## Adding New Categories

You can add new categories and define its structure like:

~~~yml
number_taxonomy.yml
~~~

---

## ⚠️ Important: Editing Existing Taxonomy File Names

However, editing existing taxonomy file names can raise an issue due to existing creators possibly already having used that name — and each value used by creators is stored in the database.

So when changing a file name, it raises an issue and makes their structure invalid.

---

## Rich Product Targeting

This taxonomy provides **high rich product target** for you in this format:

~~~text
https://qxel.app/category/taxonomy_1/taxonomy_2
~~~

For example:

~~~text
https://www.qxel.app/notes/calicut-university/bcom/semester-6/taxation
~~~

And all paths too will list directories and possible products too.

---

## Single Product Behavior

If only **1 product** is found in a category, then the product will show instead of inside taxonomy structures.

But when overtime adds, it changes — but still works.

---

## Credits

Thanks to **Jsdelivr** for providing the CDN
