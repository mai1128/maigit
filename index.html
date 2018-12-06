<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>ルーレット</title>
    <link rel="stylesheet" href="roulette.css">
    <script src="../jquery-3.3.1.min.js"></script>
    <script>
        var start_flag = false;
        var interval_id;
        var num_list = [];
        var rand;
        var num;
        var box_max = 16;

        function start_flash_text() {
            if (start_flag === false && num_list.length > 0) {
                interval_id = setInterval(flash_text, 50);
                start_flag = true;
            }
        }

        function flash_text(){
            $('.stop').removeClass('stop').addClass('used');
            $('.run').removeClass('run');
            rand = Math.floor(Math.random() * num_list.length);
            num = num_list[rand];
console.log('run', rand, num, num_list);
            $('#' + num).addClass('run');
        }

        function stop_flash_text() {
            if (start_flag === true) {
                clearInterval(interval_id);
                start_flag = false;
                $('.run').removeClass('run').addClass('stop');
                num_list.splice(rand, 1);
            }
            
console.log('stop', rand, num, num_list);
        }

        function reset_flash_text() {
            stop_flash_text();
            $('#large div').removeClass('run stop used');
            box_make();
console.log('reset', rand, num, num_list);
        }

        function box_make() {
            $('#large').empty();
            num_list = [];
            for ( var i = 1; i <= box_max; i++) {
                $('#large').append('<div id="' + i + '">' + i + '</div>');
                num_list.push(i);
            }
console.log('reset', rand, num, num_list);
        }

        $(function() {
            box_make();
            $('#start').click(start_flash_text);
            $('#stop').click(stop_flash_text);
            $('#reset').click(reset_flash_text);
        });
    </script>
</head>
<body>
    <div id="large" class="clearfix">
        <!--<div id="1">1</div>-->
        <!--<div id="2">2</div>-->
        <!--<div id="3">3</div>-->
        <!--<div id="4">4</div>-->
    </div>
    <button id="start">start</button>
    <button id="stop">stop</button>
    <button id="reset">reset</button>
</body>
</html>
