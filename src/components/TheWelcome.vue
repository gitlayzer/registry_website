<script setup>
import WelcomeItem from '@/components/WelcomeItem.vue'
import DocumentationIcon from '@/components/icons/IconDocumentation.vue'
import ToolingIcon from '@/components/icons/IconTooling.vue'
import EcosystemIcon from '@/components/icons/IconEcosystem.vue'
import CommunityIcon from '@/components/icons/IconCommunity.vue'
import SupportIcon from '@/components/icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Docker</template>
    <h4>官方方法：docker pull nginx:alpine 或 docker pull bitnami/kubectl</h4>
    <h4>加速方法：docker pull docker.cloudimages.asia/library/nginx:alpine</h4>
    <h4>加速方法：docker pull docker.cloudimages.asia/bitnami/kubectl</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Kubernetes</template>
    <h4>官方方法：docker pull registry.k8s.io/coredns/coredns:v1.11.1</h4>
    <h4>加速方法：docker pull k8s.cloudimages.asia/coredns/coredns:v1.11.1</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>GCR</template>
    <h4>官方方法：docker pull gcr.io/username/image:tag</h4>
    <h4>加速方法：docker pull gcr.cloudimages.asia/username/image:tag</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Quay</template>
    <h4>官方方法：docker pull quay.io/username/image:tag</h4>
    <h4>加速方法：docker pull quay.cloudimages.asia/username/image:tag</h4>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>GHCR</template>
    <h4>官方方法：docker pull ghcr.io/username/image:tag</h4>
    <h4>加速方法：docker pull ghcr.cloudimages.asia/username/image:tag</h4>
  </WelcomeItem>
</template>
