$(document).ready(function () {
    $('.box').hide(); //hide
    $('.overall').show(); //set default class to be shown here, or remove to hide all
});
$('#topic').change(function () { //on change do stuff
    $('.box').hide(); //hide all with .box class
    var option = $(this).val(); //show selected option's respective element

    if (option == 'overall') {
        window.location.href = "overall.html";
    }

    if (option == 'users') {
        window.location.href = "users.html";
    }
    if (option == 'projects') {
        window.location.href = "projects.html";
    }
    if (option == 'developers') {
        window.location.href = "developers.html";
    }
    if (option == 'city') {
        window.location.href = "city.html";
    }
    if (option == 'community') {
        window.location.href = "community.html";
    }
    if (option == 'location') {
        window.location.href = "location.html";
    }

});

