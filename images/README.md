# 📁 Carpeta de Imágenes – Dynamica

Las imágenes en `/public/images/` son accesibles directamente desde el navegador
como rutas absolutas. Por ejemplo, una imagen guardada en:

```
public/images/home/hero.jpg
```

Se usa en el código así:

```jsx
<img src="/images/home/hero.jpg" alt="Dynamica Diagnóstico" />
```

---

## 📂 Estructura de Carpetas

### `/home/`
Imágenes de la página de inicio (Home).

| Archivo sugerido | Sección donde se usa |
|-----------------|----------------------|
| `hero-bg.jpg` | Fondo o imagen lateral del Hero |
| `equipo-principal.jpg` | Sección "Por qué elegirnos" |
| `instalaciones.jpg` | Sección CTA o pilares |

### `/servicios/`
Una imagen por cada servicio ofrecido.

| Archivo sugerido | Servicio |
|-----------------|---------|
| `densitometria.jpg` | Densitometría Ósea |
| `diagnostico-precoz.jpg` | Diagnóstico Precoz |
| `rayos-x.jpg` | Rayos X |
| `biopsias.jpg` | Biopsias Dirigidas |
| `resonancia.jpg` | Resonancia Magnética |
| `tomografia.jpg` | Tomografía |
| `mamografia.jpg` | Mamografía 3D |
| `ecografia.jpg` | Ecografía HD / Doppler / 4D |
| `apoyo-portada.jpg` | Portada sección Servicios de Apoyo |

### `/equipo/`
Fotos del personal médico y administrativo.

| Archivo sugerido | Persona |
|-----------------|---------|
| `dr-xxx.jpg` | Dr. [Nombre del médico] |
| `dra-xxx.jpg` | Dra. [Nombre de la médica] |
| `tecnico-xxx.jpg` | Técnico radiólogo |
| `admin-xxx.jpg` | Personal administrativo |

> ⚠️ **Formato recomendado:** JPG · 800×800 px para fotos de equipo (cuadradas, fondo neutro)

### `/conocenos/`
Imágenes para la sección "Conócenos".

| Archivo sugerido | Sección |
|-----------------|---------|
| `fundadores.jpg` | Quiénes Somos – Fundadores e Historia |
| `historia-1960.jpg` | Nuestra Historia – Primera generación |
| `historia-1990.jpg` | Nuestra Historia – Segunda generación |
| `historia-2013.jpg` | Nuestra Historia – Fundación Dynamica |
| `instalaciones-interior.jpg` | Misión y Visión |

### `/galeria/`
Fotos del edificio, equipos e instalaciones.

| Archivo sugerido | Descripción |
|-----------------|-------------|
| `edificio-fachada.jpg` | Fachada exterior Dynamica |
| `sala-espera.jpg` | Sala de espera |
| `sala-rayos-x.jpg` | Sala de Rayos X |
| `equipo-mri.jpg` | Resonador magnético |
| `equipo-tac.jpg` | Tomógrafo |

---

## 📐 Especificaciones Técnicas

| Tipo | Dimensiones | Peso máximo | Formato |
|------|------------|-------------|---------|
| Hero / Portadas | 1920×1080 px | 400 KB | JPG |
| Tarjetas de servicio | 800×500 px | 150 KB | JPG |
| Fotos de equipo | 800×800 px | 120 KB | JPG |
| Galería | 1200×800 px | 200 KB | JPG |
| Logo / Íconos | Variable | 50 KB | PNG / SVG |

> 💡 **Tip:** Usa [Squoosh](https://squoosh.app) para comprimir imágenes sin pérdida notable de calidad antes de subirlas.
