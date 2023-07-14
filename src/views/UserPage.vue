<template>
    <h1>Страница пользователя</h1>
    <div class="avatar">
        <UserAvatar />
    </div>
    <div class="userPage">
        <UserInfo />
    </div>
    <div class="userNews">
        <UserNews />
    </div>
</template>

<script>
    import UserAvatar from '@/components/UserAvatar.vue'
    import UserInfo from '@/components/UserInfo.vue'
    import UserNews from '@/components/UserNews.vue'
    export default
        {
            name: "UserPage",
            components:
            {
                UserAvatar,
                UserInfo,
                UserNews
            },
            data()
            {

            },
        }
</script>

<style>
    .avatar{
        margin: 10px;
    }

    .userPage{
        font-style: italic;
    }

    .userNews{
        font-family: Arial, Helvetica, sans-serif;
        width: 50%;
    }
</style>