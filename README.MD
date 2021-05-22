# Tổng hợp các UI, và snipet của chúng trong vscode

- CSS: Tailwind
- JS: Alpine

## Setup ban đầu

### 1. Tạo folder

1. Folder

```folder
assets/css

```

### 2. Cài tailwindcss

1.

```zsh
cd assets

npm init -y

npm install tailwindcss
```

2. Tạo file tailwind.css
   Vị trí

```file
assets/css/tailwind.css
```

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

3. Tạo file tailwind config

```zsh
npx tailwindcss init
```

4. Build file tailwind css lần đầu

```zhs
npx tailwindcss build css/tailwind.css -o css/tailwind-output.css
```

### 3. Cài Alpine JS

1. Vị trí

```folder
assets
```

2. Câu lệnh cài đặt Alpine js

```zsh
npm i alpinejs
```

### 4. Link các file css, js vào file index.html
