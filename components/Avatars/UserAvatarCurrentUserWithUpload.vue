<script setup>
import UserAvatarCurrentUser from "@/components/Avatars/UserAvatarCurrentUser.vue";
import { mdiCamera } from "@mdi/js";
import FormFilePicker from "@/components/Forms/FormFilePicker.vue";
</script>

<template>
  <UserAvatarCurrentUser class="relative">
    <div class="absolute right-0 bottom-0">
      <FormFilePicker :icon="mdiCamera" is-round-icon />
    </div>
  </UserAvatarCurrentUser>
</template>
