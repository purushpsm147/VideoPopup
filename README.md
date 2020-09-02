# VideoPopup
This HTML snippet will launch a video modal popup for a youtube or vimeo video


You can also use an anchor tab add JS or jQuery to launch the video:

<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>
<body>

<a id="video-popup-anchor" href="https://www.youtube.com/embed/A-twOC3W558"><i class="fa fa-play-circle" style="font-size: 1.5rem; padding-right: 0.5rem;"></i>Watch test video</a>
        <div class="modal fade in" id="myVideoModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
            <div class="modal-dialog video-modal-dialog">
                <div class="modal-content">
                    <div>
                        <button type="button" class="close close-video" data-dismiss="modal" aria-hidden="true"><i class="fa fa-times-circle fa-times-circle-color"></i></button>
                    </div>
                    <div class="modal-body iframe-video-body">
                        <div class="iframe-video">
                        </div>
                    </div>
                </div>
            </div>
</div>

</body>
</html>
