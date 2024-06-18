<script setup>
import WelcomeItem from '@/components/WelcomeItem.vue'
import DockerIcon from '@/components/icons/IconDocker.vue'
import QuayIcon from '@/components/icons/IconQuay.vue'
import KubernetesIcon from '@/components/icons/IconKubernetes.vue'
import GithubIcon from '@/components/icons/IconGithub.vue'
import GoogleIcon from '@/components/icons/IconGoogle.vue'
import BlogIcon from '@/components/icons/IconBlog.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DockerIcon />
    </template>
    <template #heading>Docker</template>
    <h4>官方方法：docker pull nginx:alpine</h4>
    <h4>加速方法：docker pull docker.cloudimages.asia/nginx:alpine</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <KubernetesIcon />
    </template>
    <template #heading>Kubernetes</template>
    <h4>官方方法：docker pull registry.k8s.io/coredns/coredns:v1.11.1</h4>
    <h4>加速方法：docker pull k8s.cloudimages.asia/coredns/coredns:v1.11.1</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <QuayIcon />
    </template>
    <template #heading>Quay</template>
    <h4>官方方法：docker pull quay.io/username/image:tag</h4>
    <h4>加速方法：docker pull quay.cloudimages.asia/username/image:tag</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <GithubIcon />
    </template>
    <template #heading>GHCR</template>
    <h4>官方方法：docker pull ghcr.io/username/image:tag</h4>
    <h4>加速方法：docker pull ghcr.cloudimages.asia/username/image:tag</h4>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <GoogleIcon />
    </template>
    <template #heading>GCR</template>
    <h4>官方方法：docker pull gcr.io/username/image:tag</h4>
    <h4>加速方法：docker pull gcr.cloudimages.asia/username/image:tag</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <BlogIcon />
    </template>
    <template #heading>BLOG</template>
    <h4>第一域名：https://blog.devops-engineer.com.cn</h4>
    <h4>第二域名：https://www.devops-engineer.com.cn</h4>
    <br />
  </WelcomeItem>
</template>
