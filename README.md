# VideoPopup
This HTML snippet will launch a video modal popup for a youtube or vimeo video


You can also use an anchor tab add JS or jQuery to launch the video:

<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>

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



