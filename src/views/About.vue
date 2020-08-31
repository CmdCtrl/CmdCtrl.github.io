<template>
  <div class="about">
    <div class="about-title">
      <img height="50px" src="https://themindsetproject.com.au/wp-content/uploads/2017/08/avatar-icon.png" alt="" class="avi">
      <div class="title-text-content">
        <p>About Me<p>
        <h2>Jordan Lyon</h2>
      </div>
    </div>
    <div class="content">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
          Ex enim suscipit aliquam recusandae illum autem magni commodi explicabo, 
          culpa corporis perspiciatis quod. 
          Quod vitae dolorum et blanditiis, dolore ipsam cum?</p>
      <table width="100%">
        <tr>
          <th>Skills</th>
          <th>Technologies</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>Photoshop, Blender, Unity</td>
        </tr>
        <tr>
          <td>Front-End</td>
          <td>Vue.js, HTML, CSS, JavaScript, TypeScript</td>
        </tr>
        <tr>
          <td>Back-End</td>
          <td>Node.js, MongoDB, mySQL, MariaDB</td>
        </tr>
        <tr>
          <td>System Programming</td>
          <td>C</td>
        </tr>
        <tr>
          <td>Object Oriented</td>
          <td>Java, Python</td>
        </tr>
        <tr>
          <td>Environments</td>
          <td>Eclipse, Vim, Linux</td>
        </tr>
        <tr>
          <td>Other</td>
          <td>Microsoft Office (Word, PPT, Excel), slack, git</td>
        </tr>
        </table>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Nostrum enim deserunt sapiente quae quasi sequi quam, explicabo impedit eligendi sint incidunt, 
            mollitia reprehenderit exercitationem cumque nobis.
             Eius necessitatibus provident nostrum.</p>
    </div>
  </div>
</template>

<style lang="sass" scoped>
.about
  background: #333
  padding: 3em
  border-radius: 10px
  color: white
  .about-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avi
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content p
    margin-bottom: 0
    color: rgb(210, 210, 210)
  .title-text-content h2
    margin-top: 0

.content p
  line-height: 1.5
  margin: 30px auto

table
  border-spacing: 0px
  margin: 50px auto
  tr th, tr td
    border: 1px solid white
    border-top: none
    padding: 10px
    text-align: center
    &:first-of-type
      border-left: none
    &:nth-of-type(2)
      border-right: none
</style>
