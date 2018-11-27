#  $('document').ready(function () {
#            //preenche os id pq to com sono
#            $(".main section").each(function (index, elem) {
#                $(elem).attr("id", "esp" + index)
#                $("#wrap").append($("<span></span>").text(index))
#            })
#            $("#wrap span").each(function (index, elem) {
#                $(elem).on("click", function () {
#                    $(".modal").css("visibility", "visible")
#                    document.querySelector("#esp" + index).scrollIntoView({
#
#                    })
#                })
#            })
#            $("#close").click(function () {
#                $(".modal").css("visibility", "hidden")
#            })
#        })
