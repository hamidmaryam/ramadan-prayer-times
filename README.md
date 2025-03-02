<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ramadan Prayer Times in Ras al Khaimah</title>
  <link href="https://fonts.googleapis.com/css2?family=Amiri&family=Lateef&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    body {
      font-family: 'Amiri', serif;
      background-color: #0a1f2e; /* Dark blue night sky */
      color: #f0e6d2; /* Light beige for text */
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    header {
      background-color: #1a3a4a; /* Darker blue for header */
      color: #f0e6d2;
      padding: 30px;
      text-align: center;
      border-bottom: 5px solid #d4af37; /* Gold accent */
    }

    header h1 {
      font-family: 'Lateef', cursive;
      font-size: 3rem;
      margin: 0;
    }

    header p {
      font-size: 1.5rem;
      margin: 10px 0 0;
      color: #d4af37; /* Gold color for رمضان كريم */
    }

    main {
      padding: 20px;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      background-color: #1a3a4a; /* Darker blue for container */
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
      position: relative;
      overflow: hidden;
    }

    /* Decorative moon */
    .moon {
      position: absolute;
      top: -50px;
      right: -50px;
      width: 150px;
      height: 150px;
      background-color: #f0e6d2; /* Moon color */
      border-radius: 50%;
      box-shadow: 0 0 30px rgba(240, 230, 210, 0.8);
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }

    th, td {
      padding: 12px;
      text-align: center;
      border: 1px solid #2c5367; /* Lighter blue for borders */
    }

    th {
      background-color: #2c5367; /* Lighter blue for header */
      color: #f0e6d2;
      font-size: 1.2rem;
    }

    tr:nth-child(even) {
      background-color: #1a3a4a; /* Darker blue for even rows */
    }

    tr:hover {
      background-color: #2c5367; /* Lighter blue for hover */
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: #1a3a4a; /* Darker blue for footer */
      color: #f0e6d2;
      position: fixed;
      bottom: 0;
      width: 100%;
      border-top: 3px solid #d4af37; /* Gold accent */
    }

    footer p {
      margin: 0;
      font-size: 1.1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ramadan Prayer Times in Ras al Khaimah</h1>
    <p>رمضان كريم</p>
  </header>

  <main>
    <div class="container">
      <div class="moon"></div> <!-- Decorative moon -->
      <table>
        <thead>
          <tr>
            <th>Date</th>
            <th>Day</th>
            <th>Hijri</th>
            <th>Fajr</th>
            <th>Sunrise</th>
            <th>Dhuhr</th>
            <th>Asr</th>
            <th>Maghrib</th>
            <th>Isha</th>
          </tr>
        </thead>
        <tbody>
          <!-- Prayer timings will be dynamically inserted here -->
        </tbody>
      </table>
    </div>
  </main>

  <footer>
    <p>تم الإنشاء بواسطة: مريم عبد الحميد محمد رمضان</p>
  </footer>

  <script>
    // Prayer timings data for Ras al Khaimah
    const prayerTimings = [
      { date: "01 Mar", day: "Sat", hijri: "01 Ramadan", fajr: "5:21 AM", sunrise: "6:34 AM", dhuhr: "12:30 PM", asr: "3:49 PM", maghrib: "6:20 PM", isha: "7:34 PM" },
      { date: "02 Mar", day: "Sun", hijri: "02 Ramadan", fajr: "5:20 AM", sunrise: "6:33 AM", dhuhr: "12:30 PM", asr: "3:49 PM", maghrib: "6:21 PM", isha: "7:34 PM" },
      { date: "03 Mar", day: "Mon", hijri: "03 Ramadan", fajr: "5:19 AM", sunrise: "6:32 AM", dhuhr: "12:30 PM", asr: "3:49 PM", maghrib: "6:21 PM", isha: "7:35 PM" },
      { date: "04 Mar", day: "Tue", hijri: "04 Ramadan", fajr: "5:18 AM", sunrise: "6:31 AM", dhuhr: "12:29 PM", asr: "3:49 PM", maghrib: "6:22 PM", isha: "7:35 PM" },
      { date: "05 Mar", day: "Wed", hijri: "05 Ramadan", fajr: "5:17 AM", sunrise: "6:30 AM", dhuhr: "12:29 PM", asr: "3:49 PM", maghrib: "6:22 PM", isha: "7:36 PM" },
      { date: "06 Mar", day: "Thu", hijri: "06 Ramadan", fajr: "5:16 AM", sunrise: "6:30 AM", dhuhr: "12:29 PM", asr: "3:49 PM", maghrib: "6:23 PM", isha: "7:36 PM" },
      { date: "07 Mar", day: "Fri", hijri: "07 Ramadan", fajr: "5:15 AM", sunrise: "6:29 AM", dhuhr: "12:29 PM", asr: "3:49 PM", maghrib: "6:23 PM", isha: "7:37 PM" },
      { date: "08 Mar", day: "Sat", hijri: "08 Ramadan", fajr: "5:14 AM", sunrise: "6:28 AM", dhuhr: "12:28 PM", asr: "3:49 PM", maghrib: "6:24 PM", isha: "7:37 PM" },
      { date: "09 Mar", day: "Sun", hijri: "09 Ramadan", fajr: "5:13 AM", sunrise: "6:27 AM", dhuhr: "12:28 PM", asr: "3:50 PM", maghrib: "6:24 PM", isha: "7:38 PM" },
      { date: "10 Mar", day: "Mon", hijri: "10 Ramadan", fajr: "5:12 AM", sunrise: "6:26 AM", dhuhr: "12:28 PM", asr: "3:50 PM", maghrib: "6:25 PM", isha: "7:38 PM" },
      { date: "11 Mar", day: "Tue", hijri: "11 Ramadan", fajr: "5:11 AM", sunrise: "6:25 AM", dhuhr: "12:28 PM", asr: "3:50 PM", maghrib: "6:25 PM", isha: "7:39 PM" },
      { date: "12 Mar", day: "Wed", hijri: "12 Ramadan", fajr: "5:10 AM", sunrise: "6:24 AM", dhuhr: "12:27 PM", asr: "3:50 PM", maghrib: "6:26 PM", isha: "7:39 PM" },
      { date: "13 Mar", day: "Thu", hijri: "13 Ramadan", fajr: "5:09 AM", sunrise: "6:23 AM", dhuhr: "12:27 PM", asr: "3:50 PM", maghrib: "6:26 PM", isha: "7:40 PM" },
      { date: "14 Mar", day: "Fri", hijri: "14 Ramadan", fajr: "5:08 AM", sunrise: "6:22 AM", dhuhr: "12:27 PM", asr: "3:50 PM", maghrib: "6:27 PM", isha: "7:40 PM" },
      { date: "15 Mar", day: "Sat", hijri: "15 Ramadan", fajr: "5:07 AM", sunrise: "6:21 AM", dhuhr: "12:27 PM", asr: "3:50 PM", maghrib: "6:27 PM", isha: "7:41 PM" },
      { date: "16 Mar", day: "Sun", hijri: "16 Ramadan", fajr: "5:06 AM", sunrise: "6:20 AM", dhuhr: "12:26 PM", asr: "3:50 PM", maghrib: "6:27 PM", isha: "7:41 PM" },
      { date: "17 Mar", day: "Mon", hijri: "17 Ramadan", fajr: "5:05 AM", sunrise: "6:19 AM", dhuhr: "12:26 PM", asr: "3:50 PM", maghrib: "6:28 PM", isha: "7:42 PM" },
      { date: "18 Mar", day: "Tue", hijri: "18 Ramadan", fajr: "5:04 AM", sunrise: "6:17 AM", dhuhr: "12:26 PM", asr: "3:50 PM", maghrib: "6:28 PM", isha: "7:42 PM" },
      { date: "19 Mar", day: "Wed", hijri: "19 Ramadan", fajr: "5:03 AM", sunrise: "6:16 AM", dhuhr: "12:25 PM", asr: "3:50 PM", maghrib: "6:29 PM", isha: "7:43 PM" },
      { date: "20 Mar", day: "Thu", hijri: "20 Ramadan", fajr: "5:02 AM", sunrise: "6:15 AM", dhuhr: "12:25 PM", asr: "3:50 PM", maghrib: "6:29 PM", isha: "7:43 PM" },
      { date: "21 Mar", day: "Fri", hijri: "21 Ramadan", fajr: "5:01 AM", sunrise: "6:14 AM", dhuhr: "12:25 PM", asr: "3:49 PM", maghrib: "6:30 PM", isha: "7:44 PM" },
      { date: "22 Mar", day: "Sat", hijri: "22 Ramadan", fajr: "5:00 AM", sunrise: "6:13 AM", dhuhr: "12:25 PM", asr: "3:49 PM", maghrib: "6:30 PM", isha: "7:44 PM" },
      { date: "23 Mar", day: "Sun", hijri: "23 Ramadan", fajr: "4:58 AM", sunrise: "6:12 AM", dhuhr: "12:24 PM", asr: "3:49 PM", maghrib: "6:31 PM", isha: "7:45 PM" },
      { date: "24 Mar", day: "Mon", hijri: "24 Ramadan", fajr: "4:57 AM", sunrise: "6:11 AM", dhuhr: "12:24 PM", asr: "3:49 PM", maghrib: "6:31 PM", isha: "7:45 PM" },
      { date: "25 Mar", day: "Tue", hijri: "25 Ramadan", fajr: "4:56 AM", sunrise: "6:10 AM", dhuhr: "12:24 PM", asr: "3:49 PM", maghrib: "6:31 PM", isha: "7:46 PM" },
      { date: "26 Mar", day: "Wed", hijri: "26 Ramadan", fajr: "4:55 AM", sunrise: "6:09 AM", dhuhr: "12:23 PM", asr: "3:49 PM", maghrib: "6:32 PM", isha: "7:46 PM" },
      { date: "27 Mar", day: "Thu", hijri: "27 Ramadan", fajr: "4:54 AM", sunrise: "6:08 AM", dhuhr: "12:23 PM", asr: "3:49 PM", maghrib: "6:32 PM", isha: "7:47 PM" },
      { date: "28 Mar", day: "Fri", hijri: "28 Ramadan", fajr: "4:53 AM", sunrise: "6:07 AM", dhuhr: "12:23 PM", asr: "3:49 PM", maghrib: "6:33 PM", isha: "7:47 PM" },
      { date: "29 Mar", day: "Sat", hijri: "29 Ramadan", fajr: "4:52 AM", sunrise: "6:06 AM", dhuhr: "12:22 PM", asr: "3:49 PM", maghrib: "6:33 PM", isha: "7:48 PM" },
      { date: "30 Mar", day: "Sun", hijri: "30 Ramadan", fajr: "4:51 AM", sunrise: "6:05 AM", dhuhr: "12:22 PM", asr: "3:48 PM", maghrib: "6:34 PM", isha: "7:48 PM" },
      { date: "31 Mar", day: "Mon", hijri: "01 Shawwal", fajr: "4:50 AM", sunrise: "6:04 AM", dhuhr: "12:22 PM", asr: "3:48 PM", maghrib: "6:34 PM", isha: "7:49 PM" },
    ];

    // Function to populate the table with prayer timings
    function populateTable() {
      const tbody = document.querySelector("tbody");
      prayerTimings.forEach((timing) => {
        const row = document.createElement("tr");
        row.innerHTML = `
          <td>${timing.date}</td>
          <td>${timing.day}</td>
          <td>${timing.hijri}</td>
          <td>${timing.fajr}</td>
          <td>${timing.sunrise}</td>
          <td>${timing.dhuhr}</td>
          <td>${timing.asr}</td>
          <td>${timing.maghrib}</td>
          <td>${timing.isha}</td>
        `;
        tbody.appendChild(row);
      });
    }

    // Call the function to populate the table
    populateTable();
  </script>
</body>
</html>
