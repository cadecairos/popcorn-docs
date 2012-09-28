---
title: media-events
---

# Media Events #

<p>This is a list of standard HTML5 media events and their descriptions ( these may not be implemented yet for YouTube, Vimeo, and other players/wrappers ).</p>
<br />
<table border="1">
  <tr>
    <th>Event name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><code>abort</code>
    </td>
    <td>Sent when playback is aborted; for example, if the media is playing and
      is restarted from the beginning, this event is sent.</td>
  </tr>
  <tr>
    <td><code>canplay</code>
    </td>
    <td>Sent when enough data is available that the media can be played, at least
      for a couple of frames.&nbsp; This corresponds to the <code>CAN_PLAY</code>&nbsp;<code>readyState</code>.</td>
  </tr>
  <tr>
    <td><code>canplaythrough</code>
    </td>
    <td>Sent when the ready state changes to <code>CAN_PLAY_THROUGH</code>, indicating
      that the entire media can be played without interruption, assuming the
      download rate remains at least at the current level.</td>
  </tr>
  <tr>
    <td><code>canshowcurrentframe</code>
    </td>
    <td>The current frame has loaded and can be presented.&nbsp; This corresponds
      to the <code>CAN_SHOW_CURRENT_FRAME</code>&nbsp;<code>readyState</code>.</td>
  </tr>
  <tr>
    <td><code>dataunavailable</code>
    </td>
    <td>Sent when the ready state changes to <code>DATA_UNAVAILABLE</code>.</td>
  </tr>
  <tr>
    <td><code>durationchange</code>
    </td>
    <td>The metadata has loaded or changed, indicating a change in duration of
      the media.&nbsp; This is sent, for example, when the media has loaded enough
      that the duration is known.</td>
  </tr>
  <tr>
    <td><code>emptied</code>
    </td>
    <td>The media has become empty; for example, this event is sent if the media
      has already been loaded (or partially loaded), and the <a title="HTMLMediaElement"
      rel="internal" href="https://developer.mozilla.org/en-US/docs/DOM/HTMLMediaElement"><code>load()</code></a>&nbsp;method
      is called to reload it.</td>
  </tr>
  <tr>
    <td><code>empty</code>
    </td>
    <td>Sent when an error occurs and the media is empty.</td>
  </tr>
  <tr>
    <td><code>ended</code>
    </td>
    <td>Sent when playback completes.</td>
  </tr>
  <tr>
    <td><code>error</code>
    </td>
    <td>Sent when an error occurs.&nbsp; The element's <code>error</code> attribute
      contains more information. See <a rel="custom" href="https://developer.mozilla.org/en/DOM/Media_events#Error_handling">Error handling</a> for
      details.</td>
  </tr>
  <tr>
    <td><code>loadeddata</code>
    </td>
    <td>The first frame of the media has finished loading.</td>
  </tr>
  <tr>
    <td><code>loadedmetadata</code>
    </td>
    <td>The media's metadata has finished loading; all attributes now contain
      as much useful information as they're going to.</td>
  </tr>
  <tr>
    <td><code>loadstart</code>
    </td>
    <td>Sent when loading of the media begins.</td>
  </tr>
  <tr>
    <td><code>pause</code>
    </td>
    <td>Sent when playback is paused.</td>
  </tr>
  <tr>
    <td><code>play</code>
    </td>
    <td>Sent when playback of the media starts after having been paused; that
      is, when playback is resumed after a prior <code>pause</code> event.</td>
  </tr>
  <tr>
    <td><code>playing</code>
    </td>
    <td>Sent when the media begins to play (either for the first time, after having
      been paused, or after ending and then restarting).</td>
  </tr>
  <tr>
    <td><code>progress</code>
    </td>
    <td>Sent periodically to inform interested parties of progress downloading
      the media. Information about the current amount of the media that has been
      downloaded is available in the media element's <code>buffered</code> attribute.</td>
  </tr>
  <tr>
    <td><code>ratechange</code>
    </td>
    <td>Sent when the playback speed changes.</td>
  </tr>
  <tr>
    <td><code>seeked</code>
    </td>
    <td>Sent when a seek operation completes.</td>
  </tr>
  <tr>
    <td><code>seeking</code>
    </td>
    <td>Sent when a seek operation begins.</td>
  </tr>
  <tr>
    <td><code>suspend</code>
    </td>
    <td>Sent when loading of the media is suspended; this may happen either because
      the download has completed or because it has been paused for any other
      reason.</td>
  </tr>
  <tr>
    <td><code>timeupdate</code>
    </td>
    <td>The time indicated by the element's <code>currentTime</code> attribute has
      changed.</td>
  </tr>
  <tr>
    <td><code>volumechange</code>
    </td>
    <td>Sent when the audio volume changes (both when the volume is set and when
      the <code>muted</code> attribute is changed).</td>
  </tr>
  <tr>
    <td><code>waiting</code>
    </td>
    <td>Sent when the requested operation (such as playback) is delayed pending
      the completion of another operation (such as a seek).</td>
  </tr>
</table>