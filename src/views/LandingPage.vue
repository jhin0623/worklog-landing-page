<template>
  <div class="">
    <div class="">
      <!-- Header -->
      <div class="Header">
        <p class="header-left">USER GUIDE</p>
        <p class="header-right">worklog</p>
      </div>

      <!-- Title -->
      <h1 class="">WORKLOG</h1>

      <!-- Description -->
      <p class="">
        Worklog is a powerful and intuitive time-tracking mobile application designed to enhance 
        productivity, improve transparency, and streamline project management. Whether you are a 
        developer, project manager, client, or agency leader, Worklog provides real-time insights 
        into project activities by accurately tracking working hours against specific tasks or 
        custom descriptions.
      </p>

      <p class="">
        By seamlessly integrating with Asana and Jira, Worklog eliminates the need for manual time 
        tracking and ensures that every logged hour is linked to the relevant project task. For 
        teams not using these platforms, the custom description feature allows you to log time 
        on ad-hoc or non-ticketed tasks with ease.
      </p>

    </div>
    <div class="">
      <!-- Images -->
      <div class="">
        <img src="@/assets/Mobile2.png" alt="Worklog Mobile">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'WorklogLanding'
}
</script>

<style>
.container {
  text-align: center;
  margin-top: 20%;
}
h1 {
  color: #2c3e50;
}
button {
  padding: 10px 20px;
  background-color: #42b983;
  color: white;
  border: none;
  cursor: pointer;
}
</style>
