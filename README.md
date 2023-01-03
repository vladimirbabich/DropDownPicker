# DropDownPicker
Simple React Native component
# How to use
Create 3 states:
open - boolean, if true - show dropdown list
list - array of items for dropdown list
selection - array for selected items
# Example
```
const [open, setOpen] = useState(false);
const [selection, setSelection] = useState([]);
const [list, setList] = useState(['red', 'green', 'blue']);
  ...
<DropDownPicker
  open={open}
  setOpen={setOpen}
  selection={selection}
  setSelection={setSelection}
  list={list}
/>
```

# Video
https://www.youtube.com/shorts/JihaJtdLW6g
