<script>
  let item = {
    name: "bread",
    expiry: "2025-12-01",
  };
</script>

<div class="card">
  <button>Add new item</button>
</div>
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Expiry</th>
      <th>Added</th>
      <th>Category</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>{item.name}</td>
      <td>{item.expiry}</td>
    </tr>
    <tr>
      <td>test</td>
    </tr>
  </tbody>
</table>
