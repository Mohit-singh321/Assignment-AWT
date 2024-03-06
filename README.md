# Assignment-AWT

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Event Management System</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>
  <div class="container">
    <h1 class="mt-5 mb-4">Event Management System</h1>
    <!-- Event creation form -->
    <div class="card mb-4">
      <div class="card-header">Create Event</div>
      <div class="card-body">
        <form>
          <div class="form-group">
            <label for="eventName">Event Name</label>
            <input type="text" class="form-control" id="eventName" placeholder="Enter event name">
          </div>
          <div class="form-group">
            <label for="eventDate">Date</label>
            <input type="date" class="form-control" id="eventDate">
          </div>
          <div class="form-group">
            <label for="eventTime">Time</label>
            <input type="time" class="form-control" id="eventTime">
          </div>
          <div class="form-group">
            <label for="eventLocation">Location</label>
            <input type="text" class="form-control" id="eventLocation" placeholder="Enter event location">
          </div>
          <div class="form-group">
            <label for="eventDescription">Description</label>
            <textarea class="form-control" id="eventDescription" rows="3" placeholder="Enter event description"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Create</button>
        </form>
      </div>
    </div>

    <!-- Other functionalities like event registration, schedule management, attendee management can be added similarly -->

  </div>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

