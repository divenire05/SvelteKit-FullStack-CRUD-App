<div class="authContainer">
    <form>
        <h1>Login</h1>
        <label>
            <input type="email" placeholder="Email"/>
        </label>
        <label>
            <input type="password" placeholder="Password"/>
        </label>
        <label>
            <input type="password" placeholder="Confirm Password"/>
        </label>
        <button>Submit</button>
    </form>
</div>

<style>
    .authContainer {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        flex: 1;
    }

    form {
        display: flex;
        flex-direction: column;
        gap: 14px;
        width: 400px;
        max-width: 100%;
        margin: 0 auto;
        padding: 24px;
    }

    form input {
        width: 100%;
    }

    h1 {
        text-align: center;
        font-size: 3rem;
    }

    form label {
        position: relative;
        border: solid navy 1px;
        border-radius: 5px;
    }

    form input {
        border: none;
        background: transparent;
        color: white;
        padding: 14px;
    }

    form input:focus {
        border: none;
        outline: none;
    }

    form button {
        background: navy;
        color: white;
        border: none;
        padding: 14px 0;
        border-radius: 5px;
        cursor: pointer;
        font-size: 1rem;
    }

    form button:hover {
        background: blue;
    }
</style>