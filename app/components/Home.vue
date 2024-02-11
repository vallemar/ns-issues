<template>
    <Page>
        <ActionBar>
            <Label text="Home"/>
        </ActionBar>

        <FlexboxLayout style="justify-content: center; align-items: center;">
            <FlexboxLayout class="box-shadow" style="justify-content: center; align-items: center; background-color: white;" >
                <Label text="TEST"></Label>
            </FlexboxLayout>
        </FlexboxLayout>
    </Page>
</template>

<script>

  export default {
   

};
</script>

<style>
 .box-shadow{
    box-shadow:   0px 0px 30px 0px rgba(0,0,0,0.75);
    border-radius: 12;
    padding: 12;
 }
</style>
