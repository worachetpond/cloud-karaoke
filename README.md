# cloud-karaoke
cloud based midi-audio backing track karaoke player use with DAW software to sampling midi to audio.


&nbsp; Develop for party music band who use karaoke (วงดนตรีคาราโอเกะงานเลี้ยง หรือวงอิเล็กโทน).

### Support file format
    1. Midi
    2. Multitrack sound
    3. single file backing track --aac

### Midi player concept
    1. lyric and metadata store in database.
    2. Audio file store in object storage like AWS S3.
    3. When select item to playlist client will download cache to local.