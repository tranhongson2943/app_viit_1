<template>
    <nav class="nav-pagination is-layout-flex"> <div class="pagination-number"> <a class="page-number current">1</a><a class="page-number">2</a></div><a class="next-number" >NEXT PAGE</a> </nav>
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
    color: black;
    margin-right: 4px;
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
    color: black;  
}
.pagination-number{

}
.is-layout-flex{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 2rem;
    justify-content: space-between;
}
a.text-number{
    align-items: right;
}
.current{
    background-color: #0099E5;
    color:white;
}
</style>