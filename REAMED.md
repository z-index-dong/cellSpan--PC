#### 修改别人合并单元格插件


> 使用方法
    html

        <table id="process-demo-1" class="tb tb-b c-100 c-t-center">
       
        </table>

    JS
        $('#process-demo-1').tablesMergeCell({
            cols: [0,1,2,3],
            rows:[0,1,2,3]
        });
    且table上边的class不可少
    待优化，rows,cols自动合并