<h1>Shaders</h1>

<h2>1. O que são</h2>

- São instruções criadas para que a GPU seja capaz de mostrar informações na tela
  
<h2>2. Tipos mais comuns</h2>

- Vertex and Fragment
    ![Simple Shader](./images/unlit_texture.jpg)
  - exemplos mais basicos em objetos 3d
  - os valores podem ser manipulados de diversas maneiras    
    <img src="./images/uv_texture.jpg"  width="200" height="200">
    <img src="./images/worl_position_texture.jpg"  width="200" height="200">
    <img src="./images/vertex_sin_texture.gif"  width="356" height="200">
  - até os resultados mais comuns
    ![Geometry Shader](./images/shadow_light_texture.jpg)
- Geometry 
    ![Geometry Shader](./images/geometry_texture.gif)
  - extensão sobre os shaders de frag, começou a ser usado na DX11 e possui muitas funcionalizades mais modernas como tesselation e PBR
- Pixel
  - Usado em postprocessing sua funcionalidade é similar oa frag
