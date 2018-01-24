# Bootstrap 4 fullscreen modal

An easy soltion to integrate fullscreen bootstrap modals.

## Install

### With npm

```
npm install --save bootstrap4-fullscreen-modal
```

## How you use

Just add the class *.modal-fullscreen* to your bootstrap 4 modal.

```
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-toggle="modal" data-target="#exampleModal">
    Launch fullscreen modal
</button>

<!-- Modal -->
<div class="modal fade modal-fullscreen" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">&times;</span>
                </button>
            </div>
            <div class="modal-body">
                This is a fullscreen modal
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
            </div>
        </div>
    </div>
</div>
```

## Dependencies

```
"dependencies": {
    "bootstrap": "^4.0.0",
    "jquery": "^3.3.1"
},
```

* [Bootstrap 4 ](https://getbootstrap.com/)
* [JQuery](https://jquery.com/) 

## Authors

* **Basile Bong** 

## Version

1.0.1