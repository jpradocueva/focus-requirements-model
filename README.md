# focus-requirements-model
Repository dedicated to FOCUS Requirements Model
### See deltas side-by-side
```bash
git diff --no-index --color-words availabilityzone_v1-2.md availabilityzone_v1-3.md
```

### Running code --diff in VS code

#### Step 1: Install 'code' command in PATH
1. Open VS Code
2. Press `Cmd + Shift + P` (Mac) or `Ctrl + Shift + P` (Windows/Linux) to open the Command Palette.
3. Type 

```bash
shell command
```
 and select `Shell Command: Install 'code' command in PATH` from the dropdown.

Now, you can use `code` directly from any terminal window.

#### Step 2: Use `code --diff`
1. Go to View --> terminal
2. Navigate to the directory where your files are located.

For example
```bash
cd specification/dataset/columns 
```

#### Step 3: Run the diff command
Run: (for example)

```bash
code --diff availabilityzone_v1-2.md availabilityzone_v1-3.md                                            
```
