<p align="center">
  <h3 align="center">Design Kit Modules</h3>
</p>

<br>

# <%= module.name %>
<%= module.version %>

<%= module.description %>

## Install
```
npm i --save <%= module.name %>
```

## Demos

<% _.forEach(module.demos, function(demo) { %>- [<%- demo.name %>](http://rightscale-design.github.io/<%= module.name %>/docs/<%- demo.file %>)
<% }); %>

## CSS

```css
<%= srcCSS %>
```

## Author

<%= module.author %>

## License

<%= module.license %>
