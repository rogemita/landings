# Red Origen - Sitio Jekyll

## 🚀 Cómo correr localmente

1. Instalar Ruby y Bundler (si no los tenés)
```bash
sudo apt install ruby ruby-dev build-essential
gem install bundler
```

2. Instalar dependencias
```bash
bundle install
```

3. Correr el servidor local
```bash
bundle exec jekyll serve
```

Abrí [http://localhost:4000](http://localhost:4000) para ver el sitio.


## 📂 Estructura
├── _layouts/
│   └── default.html          # Layout default
├── _includes/
│   ├── header.html           # Menú superior
│   ├── footer.html           # Footer común
│   └── whatsapp.html         # Botón flotante WhatsApp
├── _terapias/                # Coleccion de terapias
│   └── veterinaria.md        # Pagina personalizada de terapia veterinaria
├── index.md                  # Institucional (usa default.html)
├── assets/css/style.css      # Estilos
├── assets/img/...            # imagenes
├── assets/js/...             # js files
└── _config.yml               # Configuración Jekyll