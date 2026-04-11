---
title: Justin Verstijnen
description: On this website, I share all my aviation experiences
params:
  body_class: td-navbar-links-all-active home-navbar-transparent
---

{{< blocks/cover
  title="Justin Verstijnen Flight Blog"
  height="full"
  color="primary"
  image_anchor="top"
>}}

{{< param "description" >}}

<div class="td-cta-buttons my-5">
  <a class="btn btn-lg btn-primary" href="/blog/">
    Click here for my blog
  </a>
</div>

{{< /blocks/cover >}}

{{< blocks/lead color="white" >}}

On this website, I will share my aviation experiences, including both theory and practice, during my journey towards achieving a Private Pilot License (PPL).

{{< /blocks/lead >}}

{{< blocks/section color="primary" >}}

<div class="container text-center">
  <div class="row justify-content-center">

    <div class="col-lg-4 mb-4">
      <a href="/blog/" class="homepage-feature-link">
        <div class="homepage-feature-item">
          <div class="mb-3">
            <i class="fa-solid fa-file-pen fa-3x"></i>
          </div>
          <h3>Blog</h3>
          <p>
            On my technical blog, I share insights and step-by-step guides based on my professional experience, covering topics such as Microsoft Azure, Microsoft 365, Entra ID, Microsoft Intune, and more.
          </p>
        </div>
      </a>
    </div>

    <div class="col-lg-4 mb-4">
      <a href="/about/" class="homepage-feature-link">
        <div class="homepage-feature-item">
          <div class="mb-3">
            <i class="fa-solid fa-user-tie fa-3x"></i>
          </div>
          <h3>About me</h3>
          <p>
            On the About me page, I’ll introduce myself, share what I like doing, and explain the things I enjoy, both professionally and personally. You can also find my socials and other information there.
          </p>
        </div>
      </a>
    </div>

    <div class="col-lg-4 mb-4">
      <a href="/portfolio/" class="homepage-feature-link">
        <div class="homepage-feature-item">
          <div class="mb-3">
            <i class="fa-solid fa-address-card fa-3x"></i>
          </div>
          <h3>Portfolio</h3>
          <p>
            This webpage and its subpages also serve as my personal portfolio and documentation system, where I showcase what I am currently researching, discovering, and working on.
          </p>
        </div>
      </a>
    </div>

  </div>
</div>

{{< /blocks/section >}}

{{< blocks/section color="white" >}}

<div class="container my-5">
  <div class="row mb-4">
    <div class="col text-center">
      <h2>Latest blog posts</h2>
      <p class="lead">An overview of my three most recently published articles:</p>
    </div>
  </div>

  <div class="row">
    {{ range first 3 (where .Site.RegularPages.ByDate.Reverse "Section" "blog") }}
      <div class="col-md-6 col-lg-4 mb-4 d-flex">
        <div class="card homepage-post-card w-100">
          <div class="card-body d-flex flex-column">
            <h3 class="h5 card-title">
              <a href="{{ .RelPermalink }}" class="homepage-post-title">{{ .Title }}</a>
            </h3>

            {{ with .Date }}
              <p class="homepage-post-date">{{ .Format "January 2, 2006" }}</p>
            {{ end }}

            <p class="card-text flex-grow-1">
              {{ with .Description }}
                {{ . }}
              {{ else }}
                {{ .Summary | plainify | truncate 140 }}
              {{ end }}
            </p>

            <div class="mt-auto">
              <a href="{{ .RelPermalink }}" class="btn btn-primary">Read post</a>
            </div>
          </div>
        </div>
      </div>
    {{ end }}
  </div>

  <div class="row">
    <div class="col text-center mt-2">
      <a class="btn btn-outline-primary" href="/blog/">View all blog posts</a>
    </div>
  </div>
</div>

{{< /blocks/section >}}