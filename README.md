
  
  <script src="https://cdn.jsdelivr.net/npm/chart.js@2.8.0"></script>
  <script type="text/javascript" src="http://maps.google.com/maps/api/js?sensor=false"></script>


                    <div style="float:right;width:700px;height:300px;">
                        <canvas id="myChart"></canvas>
                    </div>







                    <script defer
                            src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
                    </script>

                    <script>




                        var ctx = document.getElementById('myChart').getContext('2d');
                        var chart = new Chart(ctx, {
                            // The type of chart we want to create
                            type: 'pie',

                            // The data for our dataset
                            data: {
                                labels: ['1', '2', '3', '4'],
                                datasets: [{
                                    label: 'Veri Grafiği',
                                    backgroundColor: [
                                        'rgba(255, 99, 132, 0.2)',
                                        'rgba(54, 162, 235, 0.2)',
                                        'rgba(255, 206, 86, 0.2)',

                                    ],
                                    borderColor: [
                                        'rgba(255, 99, 132, 1)',
                                        'rgba(54, 162, 235, 1)',
                                        'rgba(255, 206, 86, 1)',
                                        'rgba(75, 192, 192, 1)',
                                        'rgba(153, 102, 255, 1)',
                                        'rgba(255, 159, 64, 1)'
                                    ],
                                    data: [1,1, 1, 1]
                                }]
                            },

                            // Configuration options go here
                            options: {}
                        });




                    </script>
