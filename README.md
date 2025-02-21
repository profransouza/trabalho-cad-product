# trabalho-cad-product

# instalar o Tailwind
npm install -D tailwindcss@3
npx tailwindcss init

# executar o tailwind 
npx tailwindcss -i ./src/styles/tailwind.css -o ./src/styles/output.css --watch

/** @type {import('tailwindcss').Config} */
module.exports = {
    ### dentro da pasta src/qualquer pasta ou arquivo/qualquer arquivo.html ou js
  content: ['./src/**/*.{html,js}'],
  theme: {
    extend: {},
  },
  plugins: [],
};

 
