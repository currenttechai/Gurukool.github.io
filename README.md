mkdir hsc-edu && cd hsc-edu
npx create-strapi-app@latest backend --quickstart && npx create-next-app@latest frontend
cd backend && npm install pg && cd ../frontend && npm install @strapi/strapi axios react-query @tailwindcss/forms @ckeditor/ckeditor5-react ckeditor__ckeditor5-build-classic
