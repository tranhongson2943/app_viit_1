<template>
    <nav class="nav-pagination is-layout-flex"> <div class="pagination-number"> <a class="page-number current">1</a><a class="page-number">2</a><a class="next-number" >NEXT PAGE</a></div> </nav>
</template>
<style>
.page-number{
    background-color: #f0f0f0;
    display: inline-block;
    height: 36px;
    line-height: 36px;
    padding: 0 12px;
    border-radius: 0;
    box-shadow: none;
    text-transform: uppercase;
    font-size: 14px;
}
.pagination-number{
    display: block;
    margin: 0 8px 8px 0;
}
.next-number{
    background-color: #f0f0f0;
    display: inline-block;
    height: 36px;
    line-height: 36px;
    padding: 0 12px;
    border-radius: 0;
    box-shadow: none;
    text-transform: uppercase;
    font-size: 14px;
    margin-bottom: 0.5em;
    margin-left: 550px;
}
.is-layout-flex{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 2rem;
}
</style>