## Project Categories

### Creating Project Categories

[**POST /projectcategories.json**](https://developer.teamwork.com/projectcategories#creating_project_)

```js
tw.projectCategories.create({
	"category": {
		// --
	}
})
```

### Retrieve a single Project Category

[**GET /projectCategories/{id}.json**](https://developer.teamwork.com/projectcategories#retrieve_a_single)

```js
tw.projectCategories.get(category_id)
```

### Retrieve all Project Categories

[**GET /projectCategories.json**](https://developer.teamwork.com/projectcategories#retrieve_all_proj)

```js
tw.projectCategories.get()
```

### Updating a Project Category

[**PUT /projectCategories/{id}.json**](https://developer.teamwork.com/projectcategories#updating_a_projec)

```js
tw.projectCategories.update(category_id, {
	"category": {
		// --
	}
})
```

### Destroying a Project Category

[**DELETE /projectCategories/{id}.json**](https://developer.teamwork.com/projectcategories#destroying_a_proj)

```js
tw.projectCategories.delete(category_id)
```
